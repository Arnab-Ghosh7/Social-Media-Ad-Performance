# Social Media Ad Performance Analysis

![Power BI Dashboard](PowerBi%20.png)

## 📌 Project Overview
This project presents a deep dive into the performance of social media advertising campaigns, offering a robust analytics framework for marketing stakeholders. In an era where digital ad spend is critical to business growth, understanding the nuances of user engagement—likes, shares, clicks, and impressions—is paramount.

This repository hosts a complete end-to-end analysis solution. It begins with raw data ingestion from multiple sources (ad events, campaign details, user demographics), processes this data using advanced SQL queries to sanitise and aggregate key metrics, and culminates in a high-fidelity **Power BI** dashboard. The analysis enables stakeholders to:

*   **Visualize Real-Time Performance**: Monitor key metrics at a glance.
*   **Identify High-Converting Demographics**: Target specific age groups and genders.
*   **Optimize Budget Allocation**: Shift spend towards high-ROI campaigns.
*   **Drive Strategic Decisions**: Use data-backed insights to refine marketing strategies.

It simulates a real-world data pipeline, handling thousands of interaction records to derive actionable business intelligence.

## 📂 Project Structure
The repository is organized as follows:

- **`Data/`**: Contains the raw CSV datasets used for analysis.
    - `ad_events.csv`: Logs of user interactions (Likes, Shares, Impressions) with timestamps.
    - `ads.csv`: Information about specific ads, including platform and target demographics.
    - `campaigns.csv`: Details on campaign budgets, schedules, and status.
    - `users.csv`: Demographic data and interests of the users.
- **`SQL/`**: SQL scripts for data cleaning, transformation, and extraction.
    - `SQLQuery1.sql`: Main query script for analyzing ad events and performance metrics.
- **`PowerBi/`**: Interactive dashboards.
    - `SocialMediaAdPerformance.pbit`: Power BI Template file.
    - `SocialMediaAdPerformance.pdf`: PDF export of the report.
- **`PowerBi .png`**: Snapshot of the dashboard.

## 🛠️ Technologies Used
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/sql-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

- **SQL (Structured Query Language)**: Used for querying, joining, and aggregating datasets to extract meaningful KPIs.
- **Power BI**: Used to create interactive, visually appealing dashboards for data storytelling and trend analysis.
- **CSV / Flat Files**: Raw data storage format for lightweight experimentation.

## 📊 Key Insights & Features
The analysis covers several key performance indicators (KPIs):
- **Ad Engagement**: Tracking Likes, Shares, Comments, and Clicks across different ads.
- **Demographic Targeting**: Understanding which age groups and genders respond best to specific campaigns.
- **Campaign ROI**: Evaluating the effectiveness of budget allocation.
- **Temporal Trends**: Analyzing peak engagement times (Day of Week, Time of Day).

## 🚀 How to Use
1.  **Data Setup**: Ensure the CSV files in the `Data/` folder are accessible.
2.  **SQL Analysis**:
    - Import the CSV files into your preferred SQL database (e.g., SQL Server, MySQL).
    - Open `SQL/SQLQuery1.sql` and execute the queries to explore the data.
3.  **Power BI Dashboard**:
    - Open `PowerBi/SocialMediaAdPerformance.pbit` in Power BI Desktop.
    - If prompted, connect to the data sources (CSV files in `Data/`).
    - Explore the interactive visualizations.

## 📜 License
This project is open-source. Please see the `LICENSE` file for more details.

## Author
Arnab Ghosh
