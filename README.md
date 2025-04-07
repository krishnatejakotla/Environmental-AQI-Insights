# Environmental-AQI-Insights

## Overview

Environmental-AQI-Insights is a Power BI dashboard for analyzing global air quality data (AQI). This project leverages Power BI’s interactive visualizations to provide insights into the global PM2.5 AQI levels and their distribution across various countries. The data is processed using **Azure** services, ensuring robust scalability and data management.

The dashboard offers key insights into:
- AQI Category distributions
- Regional AQI levels
- Analysis of global pollution trends by country

## Dataset

The dataset used for this project is the **Global Air Pollution Dataset** that contains pollution data for multiple countries. The data is stored on **Azure Blob Storage**.

Dataset link: [Global Air Pollution Dataset] ##(https://tejasalesdata.blob.core.windows.net/rawdata/global%20air%20pollution%20dataset.csv)

## Azure Integration

The data for this project is hosted on **Azure Blob Storage**, and the processing involves leveraging Azure tools to ensure smooth data flow and integration with Power BI.

1. **Azure Storage Account**: The data is stored in an Azure Blob Storage container called **rawdata**. This container is set to allow public access, making it easily accessible for integration with Power BI.
2. **Azure Data Factory**: Azure Data Factory was used to manage and prepare the data for Power BI. It facilitated the process of data extraction, transformation, and loading (ETL) to ensure high-quality, cleaned data.
3. **Power BI**: The dashboard was created using Power BI Desktop, with interactive visualizations to highlight key trends in the AQI data across different countries.

## Key Features

- **AQI Categories**: Includes AQI levels such as Good, Moderate, Unhealthy, Hazardous, and Very Unhealthy.
- **Country-wise Analysis**: A country-based AQI distribution showing pollution levels globally.
- **Interactive Dashboard**: The dashboard is designed to provide an interactive and insightful view of air quality levels across the world.

## Features of the Dashboard

1. **Pollution Categories by Country**: A bar chart that displays the number of countries within each AQI category.
2. **Average AQI by Category**: A donut chart that shows the average AQI value within each category, highlighting how countries are distributed across different pollution levels.
3. **Regional Insights**: A map that provides a geographic breakdown of PM2.5 AQI levels across different regions.
4. **AQI Trends**: A line chart visualizing the AQI values over time across different countries.

## How to Run

1. Download the dataset from the link above or access it directly through Azure.
2. Open **Power BI Desktop**.
3. Import the dataset into Power BI using **Get Data** from Azure.
4. Build the dashboard as per the insights described.
5. Save and publish the report to Power BI service for online access.

## Conclusion

This project provides an insightful and interactive analysis of global air quality data, leveraging both **Power BI** and **Azure** services. By combining these technologies, the dashboard offers a comprehensive view of AQI distribution across the globe, making it easier for individuals, organizations, and governments to understand and act on environmental issues.

---

Feel free to clone the repository, explore the data, and interact with the dashboard!

## Contact

- **LinkedIn**: [Krishna Teja Reddy Kotla](https://www.linkedin.com/in/krishnatejakotla/)
- **Email**: [krishnatejareddy.kotla@gmail.com](mailto:krishnatejareddy.kotla@gmail.com)
