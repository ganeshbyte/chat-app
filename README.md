# ChatApp

# .NET CLI Commands Guide

## Checking .NET SDKs

```bash
dotnet --info
```

This command displays detailed information about the installed .NET SDKs, including:

- SDK versions
- Runtime versions
- Host information
- System environment

## Creating a Solution File

```bash
dotnet new sln
```

This command creates a new solution file (.sln) in the current directory. Solution files are used to:

- Organize multiple projects
- Group related projects together
- Manage project dependencies

## Creating a Web API Project

```bash
dotnet new webapi -o API
```

Command breakdown:

- `dotnet new` - Creates a new project
- `webapi` - Specifies the template type
- `-o API` - Creates output directory named "API"

### Generated Project Structure

- Controllers/ - Contains API controllers
- Properties/ - Launch and debug settings
- appsettings.json - Application configuration
- Program.cs - Application entry point
- API.csproj - Project file

<aside>
After creating the Web API project, you can add it to your solution using:

```bash
dotnet sln add API/API.csproj
```

</aside>


