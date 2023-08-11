# 📊 Dataset Repository for PowerBI Dashboards

Welcome to the **Dataset Repository**, your source for storing datasets to seamlessly reload them into PowerBI and craft stunning dashboards! 🚀

## Description 📋

This repository serves as a centralized hub for all your datasets, enabling effortless integration with PowerBI for the creation of captivating and insightful dashboards.

## Getting Started 🚀

Follow these simple steps to get started with using the datasets in PowerBI:

1. Open the dataset CSV file in this repository.
   - Click the :page_facing_up: `Raw` icon.
   - Copy the link of the page containing the raw dataset to your local machine.
2. Load the desired dataset into PowerBI.
3. Design and build your customized dashboard.

## Features ✨

- Centralized dataset storage.
- Quick and easy integration with PowerBI.
- Empowers the creation of impactful dashboards.

## Usage 📊

Explore the datasets and harness the power of PowerBI to generate engaging visualizations. Here's an example of loading a dataset in PowerBI:
1. Open PowerBI.
2. Click :arrow_down: `Get Data`.
3. Search and Select **Web**.
4. Paste the link of your raw CSV hosted in the repository, e.g: `https://raw.githubusercontent.com/eaedk/dataset-GLEN/main/Train.csv`.

## 📈 BI Requirements

1. Total number of people who took the survey.
2. Total number of people with cell phone access.
3. Total number of people without cell phone access.
4. Education level breakdown by job type.
5. Bank account ownership based on the relationship with the head.
6. Percentage of bank accounts by location and education type.
7. Household size analysis by job type.
    - Ability to filter by country 🌍
    - Ability to filter by year 📅

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

## Contributing 👥

Contributions are welcomed! To contribute to this project:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a pull request.

## Contributors 👥

| [<img src="https://avatars.githubusercontent.com/u/28601730?v=4" width="100px;"/><br /><sub>Emmanuel KOUPOH</sub>](https://github.com/eaedk)<br />[<img src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png" width="24" />](https://www.google.com/url?q=https://www.linkedin.com/in/esa%25C3%25AFe-alain-emmanuel-dina-koupoh-7b974a17a/&sa=D&source=editors&ust=1651145136758789&usg=AOvVaw1tHt3Vf1kVU552N2lwtdOL) | [<img src="https://media.licdn.com/dms/image/C4D03AQFM12lrD91YsA/profile-displayphoto-shrink_800_800/0/1663840068518?e=1697068800&v=beta&t=ZEKOlqWQtbq9nM-Djs1RdvoklJPv2nYx-gm8GCdgcG4" width="100px;"/><br /><sub>Glen ANUM</sub>](https://github.com/GITHUB_USERNAME)<br />[<img src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png" width="24" />](https://www.linkedin.com/in/glen-anum-002245203/) | [<img src="CONTRIBUTOR_IMAGE_URL" width="100px;"/><br /><sub>CONTRIBUTOR NAME</sub>](https://github.com/GITHUB_USERNAME)<br />[<img src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png" width="24" />](https://www.linkedin.com/in/LINKEDIN_USERNAME/) | [<img src="CONTRIBUTOR_IMAGE_URL" width="100px;"/><br /><sub>CONTRIBUTOR NAME</sub>](https://github.com/GITHUB_USERNAME)<br />[<img src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png" width="24" />](https://www.linkedin.com/in/LINKEDIN_USERNAME/) | [<img src="CONTRIBUTOR_IMAGE_URL" width="100px;"/><br /><sub>CONTRIBUTOR NAME</sub>](https://github.com/GITHUB_USERNAME)<br />[<img src="https://img.icons8.com/ios-glyphs/30/000000/linkedin.png" width="24" />](https://www.linkedin.com/in/LINKEDIN_USERNAME/) |
| :---: | :---: | :---: | :---: | :---: |

## License 📄

This project is licensed under the [MIT License](LICENSE).

## Contact 📧

For any questions or suggestions, feel free to reach out at your.email@example.com. 👋
