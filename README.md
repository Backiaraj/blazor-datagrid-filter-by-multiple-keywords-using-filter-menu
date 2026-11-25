# Blazor DataGrid — Filter by Multiple Keywords using Filter Menu

A sample Blazor application demonstrating how to perform filtering on a [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) column with multiple values programmatically using the [Blazor MultiSelect Dropdown](https://www.syncfusion.com/blazor-components/blazor-multiselect-dropdown) component in a custom filter menu.

## Overview

This repository demonstrates how to implement advanced filtering in a Blazor DataGrid using the Syncfusion components. Instead of using the default filter operator UI, this sample replaces the filter template for the "Customer Name" column with a `Blazor MultiSelect Dropdown` component, enabling users to select multiple values at once and filter the grid programmatically.

The filtering is performed using the Blazor DataGrid's `FilterByColumnAsync` method with the `or` logical operator, allowing flexible data queries across multiple keywords.

## Features

- **Multi-select filtering**: Filter DataGrid columns using a multi-select dropdown with checkboxes
- **Custom filter templates**: Replace default filter UI with custom Syncfusion components
- **Programmatic filtering**: Use `FilterByColumnAsync` to apply complex filter logic
- **User-friendly UI**: Intuitive checkbox-based selection for multiple filter values
- **Select All functionality**: Built-in "Select All" option in the multi-select component
- **Sample data**: Pre-populated grid with realistic order data

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`FilterMenu.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd blazor-datagrid-filter-by-multiple-keywords-using-filter-menu
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/filter-menu

**Online example**: https://blazor.syncfusion.com/demos/datagrid/filter-menu?theme=fluent2
