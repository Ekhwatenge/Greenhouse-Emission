# Greenhouse Gas Emissions Analysis

## Introduction
This repository contains an analysis of greenhouse gas emissions data for various countries over time. The data includes carbon dioxide (CO2) emissions without land use, land-use change, and forestry (LULUCF), measured in kilotonnes of CO2 equivalent. The analysis focuses on trends, comparisons, and insights into emissions patterns.

## Data Source
The dataset used in this analysis is titled `greenhouse_gas_inventory_data_data.csv`. It includes the following columns:

- `country_or_area`: Name of the country.
- `year`: Year of the recorded emissions.
- `value`: Emissions value in kilotonnes of CO2 equivalent.
- `category`: Category of the emissions (e.g., CO2 emissions without LULUCF).

## Features
The repository provides:

- **Data Cleaning and Preparation**:
    - Standardized column names and data types.
    - Added calculated metrics such as annual growth rates of emissions.

- **Exploratory Data Analysis (EDA)**:
    - Trends in emissions over time for each country.
    - Comparative analysis across countries.
    - Identification of top emitters for specific years.

- **Visualizations**:
    - Time-series plots for individual countries.
    - Bar charts highlighting top emitters.
    - Boxplots for cross-country comparisons.

- **Descriptive Statistics**:
    - Summary statistics for emissions by country and globally.

- **Reproducible Python Code**:
    - All analysis steps are implemented in Python, ensuring transparency and reproducibility.

## Repository Structure

