# Copilot Agent Demo

An ASP.NET Core MVC web application demonstrating GitHub Copilot agent capabilities.

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)

## Getting Started

```bash
cd CopilotAgentDemo
dotnet run
```

The application will start and be available at `https://localhost:5001` (or `http://localhost:5000`).

## Project Structure

```
CopilotAgentDemo/
├── Controllers/       # MVC controllers
├── Models/            # Data models
├── Views/             # Razor view templates
├── wwwroot/           # Static assets (CSS, JS, images)
├── Program.cs         # Application entry point
└── appsettings.json   # Configuration
```

## Building

```bash
cd CopilotAgentDemo
dotnet build
```

## Running Tests

```bash
dotnet test
```
