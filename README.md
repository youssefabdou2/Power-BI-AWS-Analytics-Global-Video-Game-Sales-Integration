Power BI & AWS Analytics: Global Video Game Sales Integration
This repository features a comprehensive Power BI project that integrates Amazon Web Services (AWS) cloud data with advanced reporting. The project analyzes global Video Game Sales across various regions and publishers, demonstrating how to bridge the gap between cloud data lakes and interactive business intelligence.

## Project Architecture
The pipeline connects AWS big data storage to Power BI for scalable, high-performance reporting.

1. Setup and Configuration (AWS & Power BI)
To establish a secure and robust connection, the following steps were implemented:

Amazon Glue & Athena: Configured AWS Glue to manage the data catalog and used Amazon Athena as the query engine for the game sales dataset.

Security & IAM: Created a dedicated AWS IAM User with least-privilege permissions to ensure secure data transit.

Simba Connector: Installed and configured the Simba Athena ODBC Driver to enable Power BI Desktop to communicate directly with the AWS environment.

2. Data Preparation & ETL
Raw gaming data was refined using Power Query Editor to ensure accuracy across thousands of records:

Year Column Cleaning: Addressed inconsistencies in the release year data to ensure accurate time-series analysis.

Unpivot Transformation: Applied the Unpivot functionality to regional sales columns (NA, EU, JP, Other), allowing for dynamic regional filtering via a single slicer.

Troubleshooting: Documented and resolved common connectivity and data load issues at both the AWS source level and within the Power BI engine.

3. Visualization & UI/UX
The dashboard utilizes modern Power BI features to enhance data storytelling:

Navigation: Integrated Bookmarks and Bookmark Navigators for a fluid, app-like user experience.

Market Distribution: Utilized Pie Charts to visualize the composition of market share by region and publisher, providing a clear breakdown of global sales distribution.

UI Formatting: Customized the Filters Pane and cards for maximum usability and professional aesthetics.

<img width="1253" height="703" alt="Image" src="https://github.com/user-attachments/assets/304bf723-cb11-4177-ad7a-4bcb7ded3beb" />           


 <img width="1265" height="710" alt="Image" src="https://github.com/user-attachments/assets/1238ed2a-bc57-4a39-9454-fac5dde3ff7c" /> 
