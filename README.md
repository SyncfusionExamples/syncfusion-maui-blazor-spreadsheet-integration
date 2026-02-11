# syncfusion-maui-blazor-spreadsheet-integration

This repository contains a complete sample demonstrating how to integrate the Syncfusion Blazor Spreadsheet component inside a .NET MAUI Blazor Hybrid application. It showcases how to load and interact with Excel files using the web‑based Syncfusion Spreadsheet UI hosted inside a native MAUI application—providing a seamless, Excel‑like experience across Windows, Android, iOS, and macOS.

## Prerequisites 

Before you begin, make sure you have: 

- [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) with the required workloads:
    - [Mobile development with .NET](https://learn.microsoft.com/en-us/dotnet/maui/get-started/installation?view=net-maui-10.0&tabs=visual-studio) 
    - [ASP.NET and web development](https://dotnet.microsoft.com/en-us/apps/aspnet) 

- [.NET 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) SDK or later installed. 

## How to run this application

1. **Clone the Repository**

   ```bash
   git clone https://github.com/SyncfusionExamples/syncfusion-maui-blazor-spreadsheet-integration
   ```

2. **Locate the MAUI Project**

    Inside the repository, you will find a folder named **BlazorHybridMAUI**, which contains the complete .NET MAUI Blazor Hybrid project along with the solution file (.slnx). Simply navigate into this folder and open the solution in Visual Studio 2026 to begin working with the project.

2. **Run the Project**

    After opening the solution in Visual Studio, you can run the app on different platforms using the target selector.

    **✔ Selecting the Target Platform**

    Visual Studio displays a **Run Target Dropdown** at the top toolbar.
    This allows you to choose which device or platform you want to run the MAUI app on.
    
    **Available Targets:**

    - ✔ Window Machine
    - ✔ Android Emulator
    - ✔ iOS Remote device 
    - ✔ iOS Simulator

📌 **Notes**

- Ensure the Sample.xlsx file exists inside **wwwroot/**
- Syncfusion scripts & styles must be correctly referenced in **index.html**
- You can replace **Sample.xlsx** with your own workbook file