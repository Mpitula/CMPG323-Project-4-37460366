# CMPG323-Project-4-37460366

## This project automates User Acceptance Testing (UAT) using UiPath

**Overview**

This UiPath project automates the Create, Read, Update, and Delete (CRUD) operations on a web application for managing clients and projects, using data from an Excel file. The automation also updates the Excel file with the results of each operation, showing whether it passed or failed.

## Project Description

**The project is designed to:**

+ Retrieve client and project data from an Excel sheet.
+ Perform CRUD operations on a web application.
+ Create: Add new clients and projects based on the Excel data.
+ Read: Verifies that clients and projects were successfully created.
+ Update: Edits existing client and project records.
+ Delete: Removes clients and projects from the web application.
+ For each operation, if the action was successful or failed, it updates the corresponding row in the Excel file, marking a column (TestPassed) as TRUE or FALSE.

## Prerequisites

+ UiPath Studio (version 2023 or later).
+ UiPath Excel Activities package installed.
+ Access to the [web application](https://nwutechtrendstelemetryportalmvc.azurewebsites.net/) where the CRUD operations will be performed.
+ A configured Excel file [NWU Tech Trends Data. xlsx](https://github.com/Mpitula/CMPG323-Project-4-37460366/blob/58157145444a5a8974a17da47d20c2ce9261d08a/NWU%20Tech%20Trends%20Data.xlsx) with the client information.
+ Email - Alonemapitlula@gmail.com
+ Password - Alone@12

## How to Use the UiPath RPA Test Automation

**Follow these steps to use the UiPath RPA automation for UAT:**

1. Clone the GitHub repository to your local machine.
2. Install UiPath Studio Community Edition if not already installed.
3. Open UiPath Studio and load the NWU Tech Trends Telemetry Portal – User Acceptance Testing process.
4. Prepare the Excel test data file with input and desired output data.
5. Run the UiPath process to automate the UAT tasks.

## Documentation

[Reference List](https://github.com/Mpitula/CMPG323-Project-4-37460366/blob/0e0853a990df0d18e81eb4d7c68e9f63e8349f49/Project%204%20References.docx)

**References:**
1.	UiPath. (2023) Excel Automation in UiPath. Available at: https://docs.uipath.com/activities/other/latest?fallbackReason=invalidPublicationType&isFallback=true&fallbackCount=1 (Accessed: 1 September 2024).
2.	UiPath. (2023) Read Range Activity in Excel. Available at: https://docs.uipath.com/activities/docs/read-range  (Accessed: 1 September 2024).
3.	UiPath. (2023) For Each Row Activity in UiPath. Available at: https://docs.uipath.com/activities/docs/for-each-row-in-datatable  (Accessed: 1 September 2024).
4.	UiPath. (2023) Write Range Activity in Excel. Available at: https://docs.uipath.com/activities/docs/write-range (Accessed: 1 September 2024).
5.	UiPath. (2023) Type into Activity. Available at: https://docs.uipath.com/activities/docs/type-into (Accessed: 1 September 2024).
6.	UiPath. (2023) Element Exists Activity. Available at: https://docs.uipath.com/activities/docs/element-exists (Accessed: 1 September 2024).
7.	UiPath. (2023) How to Automate Web Forms in UiPath. Available at: https://www.uipath.com/learning/video-tutorials/web-automation (Accessed: 1 September 2024).
8.	UiPath. (2023) Data Scraping Wizard in UiPath. Available at: https://docs.uipath.com/studio/docs/about-data-scraping (Accessed: 1 September 2024).
9.	UiPath. (2023) Try-Catch Activity in UiPath. Available at: https://docs.uipath.com/activities/docs/try-catch (Accessed: 1 September 2024).
10.	UiPath. (2023) Automating CRUD Operations in UiPath. Available at: https://docs.uipath.com/studio/docs/automating-crud-operations (Accessed: 1 September 2024).

## Contact Information

For any issues or queries regarding the project, please contact: Alonemapitlula@gmail.com
