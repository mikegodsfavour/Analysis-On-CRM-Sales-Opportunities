# **ANALYSIS ON CRM SALES OPPORTUNITIES**
This is an Excel project that analyzes a fictitious B2B sales pipeline dataset from a computer hardware company, focusing on sales team performance, agent productivity, quarterly trends, and product win rates.

## Table of Contents

[Project Overview](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#project-overview)

[Project Scope](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#project-scope)

[Project Objectives](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#project-objectives)

[Expected Outcome](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#expected-outcome)

[Document Purpose](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#document-purpose)

[Use Case](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#use-case)

[Data Source](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#data-source)

[Data Cleaning and Processing](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#data-cleaning-and-processing)

[Data Analysis](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#data-analysis)

[Data Visualization](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#data-visualization)

[Recommendation](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#recommendation)

[Conclusion](https://github.com/mikegodsfavour/Analysis-On-CRM-Sales-Opportunities/edit/main/README.md#conclusion)

## Project Overview

This project analyzes B2B sales pipeline data from a fictitious computer hardware company. Using Excel with PivotTables, PivotCharts, and dashboards, the project provides insights into sales team performance, agent productivity, product win rates, and quarterly trends. The results can support strategic decisions, improve sales effectiveness, and enhance business performance.

## Project Scope

The scope of this project covers the analysis of a fictitious company’s B2B sales pipeline data using Excel. The dataset includes information on accounts, products, sales teams, sales agents, and sales opportunities

**Within this scope, the project focuses on:**

- Sales team performance (revenue, win rates, pipeline value)

- Agent performance (top vs. lagging performers)

- Quarterly sales trends (growth/decline patterns)

- Product performance (win rates by product)

- An interactive dashboard

The scope is limited to sales performance analysis and does not include predictive modeling or external market data.

## Project Objectives

The purpose of this project is to transform raw B2B sales pipeline data into meaningful insights that can guide sales strategy and improve performance. By using Excel features such as PivotTables, PivotCharts, and dashboards, the project seeks to highlight key trends and performance indicators.

**The specific objectives are to:**

- Measure and compare sales team performance.

- Identify top-performing and lagging sales agents.

- Analyze quarterly sales trends in opportunities and revenue.

## Expected Outcome
The goal of this project is to turn raw B2B sales pipeline data into practical insights that can improve decision-making and sales effectiveness. By applying Excel tools such as PivotTables, PivotCharts, and dashboards, the analysis will highlight key performance areas and opportunities for improvement.

**The expected outcomes include:**

- A clear understanding of sales team performance, showing which teams generate the most revenue and maintain stronger win rates.

- Identification of top-performing and underperforming agents, supporting targeted training and performance management.

- Visibility into quarterly sales patterns, revealing growth, decline, or seasonal trends.

- Insights into product performance, identifying which products have higher win rates and revenue contribution.

- An interactive Excel dashboard that enables stakeholders to explore the data and make informed business decisions.

## Document Purpose
The purpose of this document is to provide a clear understanding of the B2B sales pipeline analysis project, its scope, and the insights it delivers. It serves as a guide for anyone reviewing the project, ensuring they understand why it was created and how it can be used.

## Use Case
This project demonstrates how Excel can be used to analyze a B2B sales pipeline for a fictitious computer hardware company. It provides value by:

- Helping management track sales performance and guide strategy.

- Enabling sales teams and agents to measure progress and improve results.

- Allowing marketing teams to identify high-demand products and plan targeted campaigns.

- Supporting data-driven decisions on pricing, promotions, and resource allocation.

## Data Source
The dataset for this project is sourced from the [Maven Analytics website](https://app.mavenanalytics.io/datasets?search=crm+sales) platform. Designed specifically for practice and learning purposes, it simulates a CRM sales opportunities dataset for a fictitious computer hardware company. The dataset was downloaded in CSV format and contains 4 related tables with a total of 1,000+ rows of sales pipeline data.

- Accounts Table contain information about accounts, and it has 86 rows and 7 columns. Which is Account, Sector, Year_established, Revenue, Employees, Office_location,	Subsidiary_of

- Products Table contain information about products, and it has 8 rows and 3 columns. Which is Products, Series, Sales Price

- Sales Teams Table contain information about sales teams, and it has 36 rows and 3 columns. Which is Sales Agent, Manager, Regional Office.

- Sales Opportunities Table contain information about sales opportunities, and it has 8,801 rows and 8 columns. Which is Opportunity ID, Account, Product, Sales Agent, deal Stage, Engage Date, Close Date,  Close Value.

## Data Cleaning and Processing
The dataset was initially provided in a ZIP file, which contained the raw data in CSV format. To make it easier to work with, the CSV files were exported and organized into Excel worksheets. These worksheets held four main tables: Accounts, Products, Sales Teams, and Sales Opportunities.

**The following steps were carried out to prepare the dataset for analysis:**

**1. Table Integration**
Used VLOOKUP to connect the four tables together using their unique identifiers. The central table, Sales Opportunities (Sales Pipeline), carried the key identifiers including Opportunity ID, Accounts, Products, and Sales Agent. This made it possible to combine information from all supporting tables into one complete dataset.

**2. Data Cleaning**

- Removed missing and incomplete records to ensure accuracy.

- Verified and standardized column formats, especially dates and numeric fields.

- Checked for consistency across related tables.

**3. Analysis Preparation**
With the cleaned and combined dataset, Excel tools were applied to explore insights:

- PivotTables were used to summarize sales performance, product outcomes, and team contributions.

- PivotCharts were created to visualize results in chart form.

- Finally, an interactive Excel Dashboard was developed to present the key findings clearly and effectively.

This process ensured that the dataset was fully prepared, reliable, and structured for meaningful analysis and visualization.

**Data Workflow**  

```mermaid
flowchart TD
    A[ZIP File] --> B[CSV Files]
    B --> C[Excel Worksheets]
    C --> D[VLOOKUP Integration]
    D --> E[Data Cleaning]
    E --> F[Sales Pipeline Table with Unique Identifiers]
    F --> G[PivotTables]
    G --> H[PivotCharts]
    H --> I[Excel Dashboard]

## Data Analysis


## Data Visualization


## Recommendation


## Conclusion


- Evaluate product win rates to determine strong and weak performers.

- Build an interactive Excel dashboard to visualize insights and support decision-making.
