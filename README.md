# Adding Annotations to Blazor Charts

## Overview

This sample demonstrates how to add annotations to a Syncfusion [Blazor Chart](https://www.syncfusion.com/blazor-components/blazor-charts). The implementation focuses on displaying custom annotation content within the chart area and positioning annotations using coordinate-based settings. The sample illustrates how annotations can be used to emphasize important data points, provide contextual information, and improve chart readability without modifying the underlying data series.

## Key Features

- Demonstrates annotation support in the Syncfusion Blazor Chart component.
- Shows how annotation elements can be rendered as part of the chart visualization.
- Includes examples of positioning annotations using point-value coordinates.
- Includes examples of positioning annotations using pixel-based coordinates.
- Uses the Syncfusion Blazor Chart annotation feature to display supplemental information directly within the chart area.
- Demonstrates annotation placement scenarios intended to highlight significant locations in the chart.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the verified solution file `AddingAnnotationToChart.sln`.
3. Restore all NuGet packages.
4. Set the appropriate startup project if Visual Studio does not automatically select it.
5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. The application will launch using the local URL configured by the project's launch settings.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory containing the application to run.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts. 

## Project Structure

- `Client/Pages/Index.razor` — contains the Syncfusion Blazor Chart implementation, chart series configuration, and annotation definitions that demonstrate annotation positioning using chart point and pixel coordinates.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor Chart Annotations documentation: https://help.syncfusion.com/chart-sdk/blazor/charts/chart-annotations

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
