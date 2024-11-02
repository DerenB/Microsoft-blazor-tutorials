# Project Structure

```
_ Base .csproj file
|___ Properties
|___|___ LaunchSettings.json
|___ wwwroot
|___|___ Bootstrap
|___|___ Images
|___ Components
|___|___ Layout
|___|___ Pages
|___|___|___ Home.razor
|___|___|___ Weather.razor
|___|___ App.razor
|___|___ Routes.razor
|___|___ _Imports.razor
|___ appsettings.json
|___ Program.cs
```

# App Settings json

- Settings that should be on in the app at run time
- Connection strings
- logging levels
- default values

# Base File

- Every dotnet file has a base `.csproj` file
- Input properties
- Settings
- .net version
- Implicit Usings
  - Don't need to repeat using statements in every file

# Components

- App.razor
  - root component
  - root HTML
  - Blazor Router
- Routes.razor
  - Defines routes between URLs
- _Imports.razor
  - Contains the using directives globally 

# Components > Layout

- Define the overall structure
- Main Layout file

# Components > Pages

- Razor pages saved here

# Program File

- Configures and Starts the App
- Middleware added

# Properties

- LaunchSettings.json
  - Configure launch settings

# www root folder

- Contains static web assets