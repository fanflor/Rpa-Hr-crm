# Rpa-Hr-crm  / RPA HR CRM System

This project is an **automated HR intake and management system** that integrates a user-friendly **HTML/JavaScript front-end** with **UiPath RPA** workflows.

## Features
- Collects employee personal and employment details via web form
- Saves input to an **Excel file** for RPA processing
- UiPath bots automate record creation, onboarding tasks, and HR updates
- Reduces manual effort and improves data accuracy

## Tech Stack
- Front-End: HTML, CSS, JavaScript
- RPA: UiPath
- Data Storage: Excel

## Usage
1. Open `index.html` in a browser to add employee data.
2. UiPath robots read the Excel file to automate HR workflows.

## How to run 
1. Download the Project
-Clone or download the project repository to your local machine.
  git clone https://github.com/fanflor/Rpa-Hr-crm.git
  cd Rpa-Hr-crm
  
2. Open the Main Workflow
-Navigate to the UiPath project folder:
  /UiPath/BlankProcess1/
-Open the Main.xaml file in UiPath Studio.

3. Configure File Paths
-Update all file path variables and arguments in the workflow to match your local environment (e.g., input/output folders, Excel file locations, or configuration files).

 Common variables to check include:

- ExcelFilePath – path to the HR data Excel file (e.g., C:\Rpa-Hr-crm\excel\EmployeeData.xlsx)

- OutputDirectory – folder for generated or processed files

- LogFilePath – optional path for logging or audit reports

4. Run the Automation
-Open the project in UiPath Studio or UiPath Assistant.
