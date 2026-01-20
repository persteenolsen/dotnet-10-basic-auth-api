# dotnet-10-basic-auth

.NET 10 - Basic HTTP Authentication API

# Last updated

- 19-01-2026

# Creates a global json

dotnet new globaljson --sdk-version 10.0.100 --force

# Try the React 19 frontend for testing the Web API

- [`The Vue 3 Client at GitHub`](https://github.com/persteenolsen/react-basic-auth-client) - The React using HTTP Basic Authentication

# Functionality of the Web App

- HTTP Basic authentication

# Tech used for creating the Web App

- A .NET 10 Web API
- A React 19 Client for the frontend
- A traditional Webhotel for hosting
- VS Code

# Development

dotnet run

# Production

Create a self contained build for production at the remote server / traditionel web hotel

dotnet publish webapi.csproj --configuration Release --runtime win-x86 --self-contained

Upload the build to remote server

At my remote servers the web.config needs to be without the folowing:

hostingModel="inprocess"



