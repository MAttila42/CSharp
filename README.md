# C#/.NET Visual Studio Code Template

This is a template to make C#/.NET projects using Visual Studio Code.

## Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [Visual Studio Code](https://code.visualstudio.com/)
- [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- And optionally the recommended extensions that are listed in the `.vscode/extensions.json` file.

## Getting Started

1. Clone this repository
2. Open the folder in Visual Studio Code
3. Open the `Program.cs` file
4. Press `F5` to run the project

## Rename the template project names

Search for all occurrences of `MyProject` and replace them with your own projects name.

## Project Structure

- `src/` - Contains the source code for the project. Additional project directories should be added here.
- `tests/` - Contains the xUnit test code for the project.
- `docs/` - Contains the [documentation](docs/documentation) for the project.
- Consider following [this gist](https://gist.github.com/davidfowl/ed7564297c61fe9ab814) when creating additional directories.

## Config

- `settings.json` - Contains required VSCode settings for the workspace.
- `extensions.json` - Contains the recommended extensions for the project.
- `omnisharp.json` - Contains the configuration for the C# extension.
- `.editorconfig` - Contains C#/.NET conventions and guidelines.
- `.gitignore` - Contains the default .NET gitignore.

## Testing

`dotnet test` - Runs the xUnit tests, or I recommend using the [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer) extension.

## Useful dotnet commands

- `dotnet new console` - Creates a new console app project.
- `dotnet build` - Builds the project.
- `dotnet run` - Runs the project.
- `dotnet test` - Runs the xUnit tests.
