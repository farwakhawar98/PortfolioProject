# COVID-19 Exploratory Data Analysis with SQL and Tableau

## Project Overview

This project presents an exploratory data analysis (EDA) of global COVID-19 data sourced from *Our World in Data*. Using SQL for data transformation and aggregation, 
I analyzed trends in cases, deaths, and infection rates across countries and over time. The insights were then translated into an interactive dashboard to support data-driven understanding of the pandemic’s global impact.

## Objectives

* Analyze global COVID-19 trends using SQL
* Calculate key metrics such as death rates and infection percentages
* Compare country-level and global statistics
* Build a dashboard to communicate insights effectively

---

## Dataset

* **Source:** Our World in Data
* **Table Used:** `CovidDeaths`
* **Key Fields:**

  * `location`
  * `date`
  * `population`
  * `total_cases`, `new_cases`
  * `total_deaths`, `new_deaths`
  * `continent`
## Key Analysis 

### 1. Global Death Percentage

Calculated the overall likelihood of death among confirmed cases globally.

**Insight:**
Provides a high-level understanding of how deadly COVID-19 has been globally.

### 2. Total Death Count by Region

Identified regions with the highest death tolls.

**Insight:**
Highlights which continents or regions were most severely impacted.

### 3. Infection Rate by Country

Measured how widely COVID-19 spread relative to population size.

**Insight:**
Reveals countries with the highest infection penetration.

### 4. Infection Trends Over Time

Tracked how infection rates evolved daily.
**Insight:**
Enables time-series analysis of the pandemic’s progression.

## Dashboard Features

* Global KPIs (Total Cases, Total Deaths, Death %)
* Country-level comparisons
* Time-series visualizations of infection rates
* Heatmaps showing regional impact
* Interactive filters (date, country, continent)

## Key Findings

* Death percentage varied significantly across regions, reflecting disparities in healthcare systems and response strategies.
* Certain countries experienced disproportionately high infection rates relative to their population.
* Peaks in infection trends aligned with known pandemic waves, validating the dataset's reliability.
* Regional aggregations revealed that global summaries can mask local severity.

## Impact & Value

* Demonstrates strong SQL skills in aggregation, filtering, and grouping
* Shows ability to translate raw data into actionable insights
* Highlights data storytelling through dashboards
* Provides a reusable framework for analyzing time-series public health data

## Tools & Technologies

* SQL Server
* Data Visualization Tool (Tableau)
* Excel (for initial exploration)

## Future Improvements

* Incorporate vaccination data for deeper analysis
* Add rolling averages to smooth trends
* Perform correlation analysis (e.g., deaths vs. healthcare capacity)

##  Screenshots

<img width="1857" height="785" alt="image" src="https://github.com/user-attachments/assets/b420584c-b838-4f9c-b51e-fa82fd8be6e9" />




