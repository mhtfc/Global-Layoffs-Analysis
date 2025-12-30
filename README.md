🌍 Global Layoffs Analysis (2020–2023)
📌 Project Overview

This project analyzes global workforce layoffs between 2020 and 2023 to uncover trends across time, geography, industry, and company maturity.
The goal is to transform raw layoff data into business-relevant insights that support strategic decision-making for leadership, HR teams, investors, and job seekers.

The analysis focuses on understanding when, where, and why large-scale layoffs occurred during and after the COVID-19 pandemic.

🎯 Business Objective

To analyze global layoff trends and provide data-driven insights that support:

Workforce planning

Hiring and restructuring decisions

Industry and geographic risk assessment

🧰 Tools & Technologies

SQL – Data cleaning, transformation, and analysis

Excel – Initial data review and validation

Tableau – Interactive dashboard development

📂 Dataset Overview

Source: Global layoffs dataset (2020–2023)

Coverage:

1,600+ companies

50+ countries

Key Fields

Company

Industry

Country

Date

Total Laid Off

Percentage Laid Off

Company Stage

Funds Raised

🧹 Data Quality & Preparation (SQL)

The raw dataset was not analysis-ready and contained multiple quality issues that could distort insights if left unresolved.

Issues Identified

Missing values in critical business fields

Inconsistent naming of industries and countries

Duplicate records

Dates stored as text instead of date format

Records with incomplete layoff information

Cleaning Approach

All data preparation was performed using SQL to ensure scalability and repeatability:

Removed duplicate records

Standardized industry and country names

Filtered out incomplete layoff records

Converted date fields and created time-based attributes

Prepared clean, structured tables for analysis and visualization

📁 SQL scripts used for cleaning and analysis are available in the /sql folder.

📊 Key Metrics (KPIs)

Total Employees Laid Off: 383,159

Companies Affected: 1,632

Countries Impacted: 51

These KPIs provide a high-level view of the scale and global reach of workforce reductions.

🔍 Key Insights
📈 Layoffs Over Time

Layoff activity remained relatively stable during 2020–2021

Significant spikes occurred in late 2022 and early 2023

Business Insight:
Layoffs tend to follow economic cycles rather than isolated company failures, reflecting post-pandemic workforce corrections after aggressive hiring.

🏢 Layoffs by Company Stage

Post-IPO companies accounted for the highest number of layoffs

Early-stage startups contributed a smaller overall share

Business Insight:
Large, mature organizations drove most layoffs, indicating strategic restructuring rather than widespread startup collapse.

🏭 Layoffs by Industry

Industries most impacted:

Consumer

Retail

Transportation

Finance

Healthcare

Business Insight:
Consumer-facing and demand-sensitive industries are more vulnerable during periods of economic uncertainty.

🌎 Layoffs by Country

The United States accounted for the majority of global layoffs

India and several European countries followed at a significant distance

Business Insight:
Countries with strong technology and corporate ecosystems experienced the largest workforce corrections.

🏆 Companies with the Highest Layoffs

Amazon

Google

Meta

Microsoft

Uber

Business Insight:
Even market-leading organizations are highly exposed to macroeconomic pressure and cost-optimization strategies.

📊 Dashboard Overview

An interactive Tableau dashboard was developed to explore:

Monthly layoff trends

Layoffs by industry, country, and company stage

Companies contributing the highest layoff volumes

📁 Dashboard screenshots are available in the /dashboard folder.

💡 Business Impact

This analysis supports decision-making for:

Leadership: Workforce planning aligned with economic cycles

HR Teams: Proactive hiring, reskilling, and retention strategies

Investors: Industry and maturity-stage risk assessment

Job Seekers: Visibility into sector-level employment volatility

✅ Strategic Recommendations

Adopt phased, data-driven hiring strategies to reduce workforce volatility

Use workforce analytics to anticipate downturns and adjust headcount early

Diversify industry exposure to manage employment risk

Prioritize reskilling and internal mobility before large-scale layoffs

📌 Project Structure
├── sql/            # Data cleaning and analysis SQL scripts
├── dashboard/      # Tableau dashboard screenshots
├── data/           # Raw and cleaned datasets (if applicable)
└── README.md

