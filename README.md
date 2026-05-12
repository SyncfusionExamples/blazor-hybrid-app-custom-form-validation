# Blazor Hybrid App with Custom Form Validation

A comprehensive sample demonstrating how to build a customer registration form in a Blazor Hybrid application using [Syncfusion<sup style="font-size:70%">&reg;</sup> Blazor components](https://www.syncfusion.com/blazor-components) with client-side validation and cross-platform support.

## Overview

This sample application showcases best practices for building forms in [Blazor Hybrid Apps (.NET MAUI)](https://blazor.syncfusion.com/documentation/getting-started/maui-blazor-app). It provides a complete working example of:

- Customer registration form with multiple input types (text, date, dropdown)
- Client-side form validation using data annotations
- Syncfusion Blazor components integrated with .NET MAUI
- Form submission handling

The sample uses a fictitious employee details scenario to demonstrate real-world form validation patterns including field requirements, string length constraints, email validation, phone number validation, and password confirmation.

## Features

- **Syncfusion Components** - Uses SfTextBox, SfDatePicker, SfComboBox, and SfButton for a polished UI
- **Data Annotations Validation** - Built-in .NET validation attributes for required fields, string length, email, and phone number patterns
- **Cross-Platform** - Supports Windows, iOS, macOS, and Android platforms
- **Responsive Design** - Bootstrap-based responsive layout
- **Password Validation** - Compare validator for password confirmation

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-hybrid-app-custom-form-validation.git
cd blazor-hybrid-app-custom-form-validation
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

- [Blazor Hybrid Documentation](https://learn.microsoft.com/en-us/aspnet/core/blazor/hybrid/)
- [.NET MAUI Documentation](https://blazor.syncfusion.com/documentation/getting-started/maui-blazor-app)
- Learn more about [Blazor form validation](https://learn.microsoft.com/en-us/aspnet/core/blazor/forms-validation)
