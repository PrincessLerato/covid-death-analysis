COVID-19 Data Analysis (SQL Server)

Project Overview
This project analyzes global COVID-19 data using SQL Server to explore trends in infections, deaths, and vaccinations across different countries and continents.

The goal is to understand how COVID-19 spread globally and identify patterns in mortality rates, infection rates, and vaccination progress.

Objectives
- Analyze total cases vs total deaths
- Measure infection rates across countries
- Identify countries with highest death counts
- Track vaccination progress over time
- Build reusable SQL queries for visualization tools (e.g., Tableau)

Dataset
The dataset includes two main tables:
- `CovidDeaths`
- `CovidVaccinations`

Data fields include:
- Location
- Date
- Total cases
- New cases
- Total deaths
- Population
- Vaccination data

---

Key Analyses Performed

1. Global Data Exploration
Explored raw COVID-19 case and death trends over time.

2. Death Percentage
Calculated likelihood of death if infected:
- (Total deaths / Total cases) * 100

3. Infection Rate
Measured percentage of population infected per country.

4. Highest Infection Rates
Identified countries with the highest infection percentages.

5. Death Counts by Country & Continent
Ranked countries and continents by total deaths.

6. Global Trends
Aggregated daily global cases and deaths over time.

7. Vaccination Analysis
Tracked rolling total vaccinations using window functions.

8. CTE Analysis
Calculated percentage of population vaccinated using a Common Table Expression.

9. Tableau View
Created a SQL view (`vw_PercentPopulationVaccinated`) for visualization purposes.

---

Key Insights

- Some countries experienced significantly higher infection rates relative to population size.
- Death rates varied widely between regions.
- Vaccination rollout shows clear differences in speed across countries.
- Rolling vaccination calculations help track progress over time.

---

SQL Techniques Used
- SELECT, WHERE, GROUP BY
- Aggregate functions (SUM, MAX, AVG)
- CASE statements
- NULLIF for safe division
- Window functions (PARTITION BY)
- CTE (Common Table Expressions)
- Views for BI tools

---

Tools Used
- SQL Server
- Tableau (for visualization preparation)

---

Author
Princess Lerato Kgoedi
Aspiring Data Analyst | SQL | Data Cleaning | Data Insights

---

Purpose
This project demonstrates SQL skills in real-world data analysis, focusing on public health data and supporting data-driven decision-making.
