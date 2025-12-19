Global Layoffs Analysis (2020–2023)

Role: Business Analyst
Tools: SQL, Excel, Tableau
Focus Areas: Data Cleaning • Exploratory Analysis • Business Insights • Dashboarding • Strategic Recommendations


##Business Context

Between 2020 and 2023, organizations worldwide announced large-scale layoffs driven by the COVID-19 pandemic, economic uncertainty, and post-pandemic market corrections.

For business leaders, HR teams, and investors, understanding where, when, and why these layoffs occurred is critical for workforce planning and risk management.

This project analyzes global layoff data to identify meaningful patterns across time, geography, industry, and company maturity, and translates those findings into business-relevant insights.


Objective:

To analyze global layoff trends and provide data-driven insights that support strategic decision-making around hiring, restructuring, and risk assessment.


Dataset Overview

Source: Global layoffs dataset (2020–2023)

Coverage: 1,600+ companies across 50+ countries



Key Fields:

Company

Industry

Country

Date

Total Laid Off

Percentage Laid Off

Company Stage

Funds Raised


Data Quality & Preparation Approach (SQL)

The raw dataset was not analysis-ready and contained several quality issues that could lead to misleading conclusions if left unaddressed.

Key Issues Identified

Missing values in critical business fields

Inconsistent naming across industries and countries

Duplicate records

Dates stored as text rather than date format

Rows with incomplete layoff information


Cleaning Approach

All data preparation was performed using SQL to ensure repeatability and scalability:

Removed duplicate records

Standardized industry and country names

Filtered out records with insufficient layoff information

Converted date fields and created time-based attributes

Prepared clean, structured tables for analysis and visualization


Key Metrics

Total Employees Laid Off: 383,159

Companies Affected: 1,632

Countries Impacted: 51

These KPIs provide a high-level view of the scale and global reach of workforce reductions.


Key Insights

Layoffs Over Time

Layoff activity remained relatively stable during 2020–2021

Significant spikes occurred in late 2022 and early 2023

This pattern reflects post-pandemic workforce corrections following aggressive hiring cycles


Business Takeaway:
Layoffs tend to follow economic cycles rather than isolated company failures.

Layoffs by Company Stage

Post-IPO companies accounted for the highest number of layoffs

Early-stage startups contributed a smaller share overall

Business Takeaway:
Large, mature organizations drove most layoffs, indicating strategic restructuring rather than widespread startup collapse.

Layoffs by Industry

Industries most impacted:

Consumer

Retail

Transportation

Finance

Healthcare

Business Takeaway:
Consumer-facing and demand-sensitive sectors were more vulnerable during periods of economic uncertainty.

Layoffs by Country

The United States accounted for the majority of global layoffs

India and several European countries followed at a significant distance

Business Takeaway:
Countries with strong technology and corporate ecosystems experienced the largest workforce corrections.


Companies with the Highest Layoffs

Amazon

Google

Meta

Microsoft

Uber

Business Takeaway:
Even market-leading organizations are highly exposed to macroeconomic pressure and cost-optimization decisions.


Dashboard Overview

An interactive Tableau dashboard was developed to help stakeholders explore:

Monthly layoff trends

Layoffs by industry, country, and company stage

Companies contributing the highest layoff volumes

Dashboard screenshots are available in the /dashboard folder.


How This Analysis Supports Business Decisions

Leadership: Enables informed workforce planning aligned with economic cycles

HR Teams: Supports proactive hiring and reskilling strategies

Investors: Highlights industry and maturity-stage risk exposure

Job Seekers: Provides visibility into sector-level employment volatility


Recommendations

Adopt phased, data-driven hiring strategies to reduce workforce volatility

Use workforce analytics to anticipate downturns and adjust headcount early

Diversify industry exposure to manage employment risk

Prioritize reskilling and internal mobility before large-scale layoffs
