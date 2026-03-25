# MVC Demo — ASP.NET Core MVC Demo

A portfolio project demonstrating the ASP.NET Core MVC pattern, built as a companion to [RPDemoApp](https://github.com/garyturna/RPDemoApp) (Razor Pages) to show familiarity with both UI approaches in the ASP.NET Core ecosystem.

## Tech Stack

- **Framework:** ASP.NET Core (.NET 10)
- **UI Pattern:** MVC (Controllers + Razor Views)
- **Language:** C#

## Concepts Demonstrated

- MVC separation of concerns — Models, Views, Controllers
- Controller actions with `IActionResult` return types
- Strongly typed Razor Views with `@model` directives
- Model binding and form handling
- Dependency injection into controllers
- Tag Helpers (`asp-for`, `asp-action`, `asp-controller`)

## Getting Started

1. Clone the repo
2. Run with `dotnet run --project MVCDemoApp`
3. Navigate to `https://localhost:5001`

## Related

- **[RPDemoApp](https://github.com/garyturna/RPDemoApp)** — companion project using Razor Pages with Dapper and SQL Server.
