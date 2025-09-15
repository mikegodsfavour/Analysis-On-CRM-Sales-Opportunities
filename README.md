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
- 
- Evaluate product win rates to determine strong and weak performers.
  
- Build an interactive Excel dashboard to visualize insights and support decision-making.

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

## Data Analysis
**1. How is each sales team performing compared to the rest?**

The setup, using managers and their sales agents in the PivotTable, allows us to evaluate the performance of each sales team compared to the rest. By grouping agents under their respective managers, we can see which teams are contributing strongly and which ones are lagging.

**Insight from the analysis**

From the analysis, it becomes clear that some managers oversee teams that are consistently ahead of others in terms of contribution, while a few sales agents within certain teams stand out as top performers. This approach highlights both team-level performance and individual agent effectiveness, helping to identify strong teams and those that may need additional support.

**2. Are any sales agents lagging behind?**

The PivotTable was structured with sales agents in the rows and revenue as the value, which provided a clear view of how individual agents are performing relative to one another. This setup allowed us to see variations in contribution across all agents, highlighting both the stronger performers and those who are not keeping pace.

**Insight from the analysis**

From the analysis, it becomes clear that while some agents generate a high share of revenue, others are lagging behind compared to their peers. This information is useful for identifying agents who may require additional support, coaching, or performance review to bring them closer in line with team expectations.

**3. Can you identify any quarter-over-quarter trends?**

I grouped the data by quarters using the engagement and close dates, with revenue as the value. This setup allowed me to compare sales performance across Q1, Q2, Q3, and Q4. By doing this, I was able to clearly see how each quarter performed and how revenue shifted over time.

**Insight from the analysis**

From the analysis, Q2 recorded the highest revenue, making it the strongest quarter of the year. Q4 followed next, showing another strong performance, while Q3 ranked third. Q1 had the lowest revenue, indicating a weaker start compared to the rest of the year. This trend shows that sales activity tends to peak in Q2, remain strong in Q4, and slow down in Q1. These insights can help in planning, especially to boost performance in the weaker quarters.

**4. Do any products have better win rates?**

A PivotTable was set up with products in the rows, deal stage in the columns, and opportunity IDs as the values. The deal stages included Engaging, Prospecting, Lost, and Won, which made it possible to see how opportunities moved across these stages for each product. This structure highlighted how many opportunities were successfully converted compared to those still in progress or lost.

**Insight from the analysis**

The result shows that some products had a higher number of opportunities reaching the Won stage, meaning they were converted into successful deals more often. Others had more opportunities stuck in Engaging or Prospecting, or ending in Lost, which lowered their overall win rates and may require stronger sales or marketing support. This helps the business focus on products that perform best while improving strategies for those that lag behind.


**5. Which product generated the most revenue?**

A PivotTable was set up with Product in the rows and Revenue in the values. This helped me identify which products generated the highest revenue compared to others.

**Insight from the analysis**

GTX Basic contributed the highest share of revenue, accounting for $4,121,351.31  of the total.

MG Advanced followed with about $3,094,260.92.
 
GTX Plus Basic made up $2,911,772.16.

MG Special contributed  $2,731,859.28 .

GTS Plus Pro had $2,016,191.36.

Finally, GTK 500 recorded the lowest with $128,566.87 of total revenue.

This shows that GTX Basic is the strongest revenue driver, while GTK 500 contributes very little. The company could focus on sustaining top-performing products while reviewing strategies for the weaker ones.

**6. Sales performance by each manager**

A PivotTable was set up with Manager in the rows and Revenue in the values. This allowed me to compare the performance of each sales manager based on the total revenue their teams generated.

**Insight from the analysis**

Summer Sewald recorded the highest revenue contribution, accounting for $3,348,224.04 of revenue.

Dustin Brinkmann followed closely with $2,650,522.82 of revenue.

Celia Rouche came next with $2,638,097.18 of revenue.

Then Malvin Marxen with $2,365,197.69 of revenue.

Rocco Neubert with $2,262,633.13 of revenue.

and finally Cara Losch, who generated the lowest revenue among the managers with $1,739,327.03 of revenue.

This shows that while some managers (like Summer Sewald and Dustin Brinkmann) are leading strongly in sales performance, others may need support or new strategies to improve their teams’ contributions.


## Data Visualization

For visualization, I designed an interactive dashboard in Excel to summarize and present the sales pipeline analysis. The dashboard is chart-based and supported with key performance indicators (KPIs) to give a quick overview of business performance.

**The main features of the dashboard are:**

- KPIs: Showing the Number of Deals and Total Revenue for quick performance tracking.

- Charts: Visuals covering sales team performance, quarterly revenue, deal stage progress, product performance, and manager contribution.

- Slicer: A product-based slicer that allows users to filter and view performance insights by specific products.

This setup makes it easy to monitor overall sales activity, identify high-performing products, and understand revenue distribution across teams and managers in a simple, interactive way.

## Recommendation

Based on the analysis, several steps can help improve sales performance and decision-making:

- Focus on High-Performing Products: Products like GTX Basic and MG Advanced should remain a priority since they bring in the most revenue. Marketing and promotions can be strengthened around them.

- Support Lower-Performing Products: Products such as GTK 500 need review. Adjustments in pricing, promotion, or sales strategies may help boost their performance.

- Strengthen Sales Teams: Identify sales agents or managers with lower results and provide targeted training, support, or resources to improve their output.

- Leverage Seasonal Trends: Since Q2 recorded the highest sales, the company should plan campaigns, stock, and promotions to maximize this period while also finding ways to improve Q1.

- Improve Deal Conversion: Deal stages show that not all opportunities move to “Won.” Focus should be placed on improving engagement and conversion strategies to reduce losses.

## Conclusion

This project analyzed a fictitious B2B sales pipeline dataset to evaluate sales team performance, product win rates, quarterly revenue trends, and overall sales outcomes. Using Excel tools such as PivotTables, PivotCharts, and Dashboards, the analysis provided clear insights into how different managers, agents, and products contribute to total revenue.

The findings highlight the best-performing products and teams, seasonal trends that affect revenue, and areas where improvement is needed. With the help of interactive dashboards and KPIs, management can easily monitor sales progress, make data-driven decisions, and design strategies that strengthen both product and team performance.

Thank You For Reading

I’m interested in a Data Analyst role in an organization where I can showcase my skills, take more responsibilities, continue to learn, an organization that I can grow with, where my work will be highly beneficial to the organization.

You can reach me on mikefavour99@gmail.com

THANK YOU

