COVID-19 Analysis (SQL Project)
Project Overview
This project analyzes global COVID-19 data using SQL to extract key insights regarding case trends, fatality rates, and vaccination progress. The queries help uncover patterns in infections, deaths, and vaccinations across different locations.

Objective
To leverage SQL queries to analyze COVID-19 trends, understand the impact of the pandemic, and derive actionable insights.

Tools & Technologies Used: 

SQL (SQL Server)
Aggregate & Window Functions
Joins & Subqueries
Common Table Expressions (CTEs)
Temporary Tables
Data Cleaning & Transformation

Key Insights & Findings:

Case Growth Trends: Identified peak infection periods across different regions.
Fatality Rate Analysis: Determined which countries had the highest mortality rates.
Vaccination Progress: Analyzed vaccination distribution and coverage over time.
Recovery Rates: Evaluated how recovery rates improved with vaccination efforts.
Percent Population Infected: Derived insights on how much of the population was infected per location.

Datasets & SQL Queries in This Repository

Datasets Used:
covid_deaths.xlsx - Contains global COVID-19 death statistics.
covid_vaccinations.xlsx - Contains global vaccination records.

SQL Queries
covid_cases_analysis.sql - Retrieves total cases, new cases, and deaths by location and date.
death_percentage.sql - Calculates the death percentage per location.
infection_rate.sql - Analyzes the percentage of the population infected per location.
highest_infection_count.sql - Finds locations with the highest number of infections.
total_deaths.sql - Aggregates total death counts by location and continent.
vaccination_progress.sql - Tracks vaccination progress using window functions.
population_vs_vaccination.sql - Uses CTEs to analyze rolling vaccination rates.
temporary_table_vaccination.sql - Uses temporary tables to store and analyze vaccination progress.

How to Use
Import the dataset into your SQL database.
Run the queries from the provided SQL scripts.
Explore and visualize the results.

Conclusion
This SQL analysis helps in understanding the COVID-19 pandemic's impact through data-driven insights, useful for policy-making and health organizations.
