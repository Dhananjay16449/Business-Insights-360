# Business-Insights-360

## Project Overview

This project was developed as part of the Power BI course at Codebasics and aims to provide a comprehensive, integrated business intelligence solution for AtliQ, a rapidly growing global company. AtliQ faced significant challenges in managing and analyzing its operational data due to the reliance on Excel spreadsheets for data analytics. The project involved transitioning their data analysis capabilities to Power BI, enabling real-time, actionable insights across multiple business domains to drive data-driven decision-making.

## Project Links

- **Live Dashboard :** [Link](https://app.powerbi.com/view?r=eyJrIjoiMmJkOTRjNjEtN2M2Ny00MDQxLWEyMTQtYzM0MjI1NmExNzQ3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
- **Dashboard Snapshots :** [Link](./reports/)

## Problem Statement

AtliQ, a business with operations expanding across multiple countries, was struggling with the increasing complexity of its operations. Despite their rapid growth, the company was relying heavily on Excel for data analysis, which was time-consuming, error-prone, and lacked scalability. This caused inefficiencies in decision-making and led to significant financial losses, particularly in their Latin American market, due to the inability to extract meaningful insights from their data in real time.

## Objective

The primary objective of this project was to transition AtliQ from its outdated Excel-based data analysis process to a more efficient and scalable solution: Power BI. The goal was to develop an interactive, dynamic, and integrated Power BI dashboard capable of providing real-time insights, improving operational efficiency, and empowering decision-makers at all levels of the business with actionable data.

## Key Features & Business Functions

- **Finance View :**
Displays Profit & Loss (P&L) statements for specific customers, products, and countries over any given time period.
Allows for the detailed analysis of financial performance, including revenue, expenses, and profitability metrics.

- **Sales View :**
Offers a detailed performance analysis based on key metrics such as Net Sales, Gross Margin, and Profitability.
Provides a Growth Matrix for assessing sales performance and profitability of individual customers, products, and regions.

- **Marketing View :**
Evaluates the performance of products in the market, focusing on metrics like Net Sales and Gross Margin.
Visualizes the profitability and growth potential of products through an interactive matrix, helping prioritize marketing efforts.

- **Supply Chain View :**
Tracks key metrics such as Forecast Accuracy, Net Error, and Risk Profiles for different segments, categories, and customers.
Assists in identifying areas of improvement for supply chain optimization and risk management.

- **Executive View :**
A high-level, consolidated dashboard that presents key insights across all business areas, providing executives with a comprehensive overview of performance and operational health.

## Project Implementation

The development of this Power BI dashboard involved several critical steps, including data extraction, transformation, modeling, and visualization. Below is a detailed overview of the technical implementation.

1. *Database Design and Setup :*
The database serves as the central repository for all business data and ensures consistency and reliability across the platform.
Developed a Snowflake schema that organizes data into related tables, optimizing for easy retrieval and analytical performance.

2. *Data Extraction and ETL Processes :*
Data was seamlessly extracted from multiple sources, including MySQL databases and Excel files, ensuring that all relevant business data could be ingested into Power BI.
Applied ETL (Extract, Transform, Load) processes to clean, standardize, and transform raw data into valuable, actionable insights. These processes ensured data consistency and improved the quality of the reports generated.

3. *Data Modeling :*
Created an advanced data model using the Snowflake schema, which integrated over ten related tables. This model enables the efficient and accurate analysis of data across various business domains.
Developed calculated columns and measures using DAX (Data Analysis Expressions) to allow for complex business calculations and deeper analytical insights.

4. *Visualization and Reporting :*
Designed interactive visualizations using Power BI, including dashboards, charts, tables, and KPIs, that allow users to explore data dynamically.
Leveraged features like slicers, bookmarks, and buttons to create user-friendly, interactive reports that allow stakeholders to drill down into specific data points and view customized views.
Integrated Power BI Services for report publishing, making it easy to share insights across teams and departments.

5. *Automation & Data Refresh :*
Implemented automated data refresh using Power BI Gateway, ensuring that the dashboard reflects the latest business data without manual intervention.
Scheduled automatic updates to keep the reports up-to-date, ensuring executives and teams always have access to the most current information.

## Technique Stacked
- *Power BI:* Used for creating dynamic dashboards, visualizations, and interactive reports.
- *MySQL:* Used as the database management system for storing and managing business data.
- *ETL Processes:* Leveraged Python and SQL for extracting and transforming data from various sources.
- *DAX (Data Analysis Expressions):* Used to create calculated columns and measures for advanced analytics.
- *Power BI Services:* Utilized for report publishing, sharing, and automated data refresh.
- *Snowflake Schema:* Adopted for efficient data organization and modeling.

## Conclusion

This project has significantly enhanced my Power BI and data analytics skills, allowing me to build a comprehensive business intelligence solution for AtliQ. It showcases the power of Power BI to turn raw data into insightful, real-time visualizations that can guide business decisions across finance, sales, marketing, and operations.

The transition from Excel-based analysis to a more sophisticated Power BI solution has greatly improved AtliQ's ability to analyze data efficiently and make informed decisions that drive business growth.
