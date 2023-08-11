# Dataset Repository for PowerBI Dashboards

Welcome to the Dataset Repository, your source for storing datasets to seamlessly reload them into PowerBI and craft stunning dashboards!

## Description

This repository serves as a centralized hub for all your datasets, enabling effortless integration with PowerBI for the creation of captivating and insightful dashboards.

## Getting Started

Follow these simple steps to get started with using the datasets in PowerBI:

1. Open the dataset CSV file in this repository, Click the `Raw icon`, Copy the link of the page containing raw dataset to your local machine.
2. Load the desired dataset into PowerBI.
3. Design and build your customized dashboard.

## Features

- Centralized dataset storage.
- Quick and easy integration with PowerBI.
- Empowers the creation of impactful dashboards.

## Usage

Explore the datasets and harness the power of PowerBI to generate engaging visualizations. Here's an example of loading a dataset in PowerBI:
1. Open PowerBI.
1. Click ` Get Data `.
1. Search and Select **Web**.
1. Paste the link of your raw CSV hosted in the repository, e.g: ` https://raw.githubusercontent.com/eaedk/dataset-GLEN/main/Train.csv `  .

# BI Requirements

Total number of People who took the survey.

Total number of cell phone access.

Total number with no cell phone access.

What is the level of Education by job type?

Bank account by a relationship with head.

Percentage of bank accounts by location and education type.

What is the Household size by job type?
- Ability to filter by country
- Ability to filter by year

<!-- ```PowerQuery
let
    Source = Folder.Files("Path to Your Local Repository"),
    #"Filtered for Excel Files" = Table.SelectRows(Source, each [Extension] = ".xlsx"),
    #"Imported Excel" = Table.AddColumn(#"Filtered for Excel Files", "Data", each Excel.Workbook([Content])),
    #"Removed Other Columns" = Table.SelectColumns(#"Imported Excel",{"Data"}),
    #"Expanded Data" = Table.ExpandTableColumn(#"Removed Other Columns", "Data", {"Sheet1"}, {"Sheet1"})
in
    #"Expanded Data"
``` -->

# Contributing
Contributions are welcomed! To contribute to this project:

1. Fork the repository.
1. Create a new branch.
1. Commit your changes.
1. Open a pull request.

# License
This project is licensed under the [MIT License]().

# Contact
For any questions or suggestions, feel free to reach out at your.email@example.com.