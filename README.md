# COVID-19 Data Analysis Project

## Overview
This project involves analyzing COVID-19 data from the `CovidDeaths$` and `CovidVaccinations$` tables in the `Portfolio project (Covid)` database. The goal is to extract meaningful insights about COVID-19's impact on different locations and continents, focusing on infection rates, death rates, and vaccination rates.

## Steps

### Step 1: Data Selection
We begin by selecting the relevant data for analysis. It is crucial to filter out grouped data entries by ensuring the continent field is not null. This allows for a more accurate analysis of individual locations.

### Step 2: Total Cases vs. Total Deaths for India
Next, we analyze the death rate for India by calculating the percentage of deaths out of total cases. This helps in understanding the severity of the pandemic in India.

### Step 3: Total Cases vs. Total Deaths for the World
We then extend the analysis globally to calculate the death rate for the entire world. This provides a broader perspective on the pandemic's impact.

### Step 4: Total Cases vs. Population
To assess the spread of COVID-19, we calculate the percentage of the population that contracted the virus. This step highlights the infection rate relative to the population size.

### Step 5: Countries with the Highest Infection Rate
We identify the countries with the highest infection rates compared to their populations. This helps in recognizing the most affected regions.

### Step 6: Death Rate for India
Focusing again on India, we calculate the death rate among COVID-19 infected individuals. This provides a detailed view of the pandemic's lethality in the country.

### Step 7: Countries with the Highest Death Count
We identify the countries with the highest death counts, offering insight into which regions experienced the most fatalities.

### Step 8: Data Breakdown by Continent
To further refine the analysis, we break down the data by continent. This helps in comparing the impact of COVID-19 across different continents.

### Step 9: Global Numbers
We calculate global totals for new cases and deaths, and determine the global death percentage. This step provides an overall summary of the pandemic's impact.

### Step 10: Rolling People Vaccinated
By joining the COVID-19 deaths data with vaccination data, we compute the rolling number of people vaccinated for each location. This helps in understanding the progress of vaccination efforts.

### Step 11: Using CTEs and Temp Tables
We utilize Common Table Expressions (CTEs) and temporary tables to structure and manipulate the data efficiently. This includes calculating the percentage of the population vaccinated.

### Step 12: Creating Views for Visualization
Finally, we create a view to store the data before visualization. This step prepares the data for easy access and analysis in visualization tools.

## Conclusion
This project provides a comprehensive analysis of COVID-19 data, highlighting key metrics such as infection rates, death rates, and vaccination progress. The insights gained from this analysis can inform public health decisions and strategies to combat the pandemic.
