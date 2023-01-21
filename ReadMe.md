# Blazor Hello World website with Visual Studio Code

This is a very basic Blazor Hello World website written in Visual Studio Code. Yes 'Code', not VS. I followed the tutorial from [Visual Studio Code for C# Developers | .NET Conf 2022](https://youtu.be/fuBi4d7k1-M?t=956). 

Blazor is a framework for building interactive client-side web UI with .NET \
More information about Blazor: [ASP.NET Core Blazor](https://learn.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-7.0) (learn.microsoft.com)

## How To

Instructions: 

1. Download and install Visual Studio Code from https://code.visualstudio.com/Download
2. Download and install the .Net SDK from https://dotnet.microsoft.com/en-us/download
3. Follow Tim's instructions from the Video

The commands I used: 

```console
dotnet new sln --name "Blazor"
dotnet new gitignore
dotnet new blazorserver --name "Server"
dotnet sln add .\Server\Server.csproj
```