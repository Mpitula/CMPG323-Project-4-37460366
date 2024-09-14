# CMPG323-Project-4-37460366

## This project automates User Acceptance Testing (UAT) using UiPath

This UiPath project automates the Create, Read, Update, and Delete (CRUD) operations on a web application for managing clients and projects, using data from an Excel file. The automation also updates the Excel file with the results of each operation, showing whether it passed or failed.

## Project Description

**The project is designed to:**

+ Retrieve client and projects data from an Excel sheet.
+ Perform CRUD operations on a web application.
+ Create: Add new clients and projects based on the Excel data.
+ Read: Verifies that clients and projects were successfully created.
+ Update: Edits existing client and project records.
+ Delete: Removes clients and projects from the web application.
+ For each operation, if the action was successful or failed, it updates the corresponding row in the Excel file, marking a column (TestPassed) as TRUE or FALSE.
