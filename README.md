# Dynamic Circular Gauge Axes

A Blazor sample demonstrating how to dynamically add multiple axes to the [Blazor Circular Gauge](https://www.syncfusion.com/blazor-components/blazor-circular-gauge) component. This example shows component re-rendering based on data changes and provides a foundation for building interactive gauge applications.

## Overview

The Blazor Circular Gauge is a powerful visualization component for displaying analytical data in a circular format. This sample shows how to leverage Blazor's component lifecycle and data binding to dynamically add axes to the gauge at runtime.

The application features a simple but effective UI: an "Add Axis" button that incrementally adds new axes to the gauge, each with a different maximum value. This pattern is useful for:

- **Real-time dashboards** that need to display variable metrics
- **Multi-metric monitoring** applications  
- **Interactive data exploration** tools
- **Learning reactive UI patterns** in Blazor

## Features

- **Dynamic Axis Rendering** — Leverage Blazor's reactive data binding to add axes without page reloads or manual DOM manipulation
- **Blazor Circular Gauge Integration** — Pre-configured, production-ready component with built-in styling and customization options
- **Interactive UI Controls** — Click-driven interface to demonstrate real-time component updates and state management
- **Clean, Minimal Design** — Focused example code with proper separation of concerns, easy to understand and extend
- **Blazor Server Rendering** — Full server-side rendering with automatic HTML client-side interactivity out of the box
- **Styled Axes** — Customizable axis styling including line width, color, and tick positioning

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-circular-gauge-dynamic-axes.git
cd blazor-circular-gauge-dynamic-axes
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/circular-gauge/axes

**Online example**: https://blazor.syncfusion.com/demos/circular-gauge/default-functionalities?theme=fluent2