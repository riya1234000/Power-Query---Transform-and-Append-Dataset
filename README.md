# Power-Query---Transform-and-Append-Dataset

# README: Power Query Automation (Transform and Append)
Overview
This workbook implements an automated Power Query ETL workflow designed to consolidate, transform, and append multi-source data tables into a unified reporting format. By using Power Query's table transformation and append capabilities, the workflow replaces manual copy-pasting with a repeatable, one-click refresh solution.

# Workflow Architecture
[ Data Sources / Files ] ──► [ Custom Transformations ] ──► [ Append Tables ] ──► [ Final Output ]
Source Ingestion: Extracts structured tables or files dynamically into a unified collection ([Table] nested structures).

# Transformations: 
Standardizes column names, data types, and applies custom filtering/cleaning functions consistently across each table before merging.

# Append (Union):
Combines rows from multiple transformed tables into a single master table.

# Load:
Populates the cleaned output directly into Excel or the Data Model for analysis.

# How to Use This Workbook
Prerequisites
Excel Version: Microsoft Excel 2016 or newer (or Excel 2010/2013 with the Power Query add-in installed).

Step-by-Step Instructions
Add / Update Source Data:

Place the source files or update the source tables referenced by the query (e.g., in the designated folder or input sheets).

Refresh the Queries:

Go to the Data tab on the Excel Ribbon.

Click Refresh All (or press Ctrl + Alt + F5).

Alternatively, open the Queries & Connections pane, right-click the target query, and select Refresh.

Verify the Output:

# Review the resulting appended table on the main worksheet to confirm all input records have processed correctly.

# Key Features & Benefits
Automated Data Consolidation: Eliminates manual appending of multiple sheets or files.

Schema Alignment: Automatically aligns columns across input sources, handling missing or additional attributes seamlessly.

Scalable Infrastructure: Easily accommodates new data batches without altering query logic.
