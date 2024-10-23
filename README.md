# -The-Relationship-between-Inflation-Unemployment-rate-in-Euro-Zone-between-2015-2023

## Overview

This project examines the relationship between inflation and unemployment in the Eurozone from 2015 to 2023. The main analysis investigates how inflation (X) and unemployment (Y) interact across 30 countries in the Eurozone during this period, utilizing various statistical methods and visualization tools. The code is written in **R**.

## Project Structure

- **`DATA.Rmd`**: This is the main R Markdown file containing the code for data preprocessing, analysis, and visualization. The code covers the following key steps:
  1. Data Loading and Preparation
  2. Descriptive Analysis of Inflation and Unemployment Variables
  3. Summary Statistics and Distribution Plots
  4. Regression Models (Linear and Quadratic Fits)
  5. Fixed Effects Models by Country and Year
  6. Visualizations of Trends and Relationships Between Variables

- **Data**: The data includes country-level inflation and unemployment rates sourced from public Eurozone datasets. It was preprocessed to ensure consistency across years and countries.

## Key Components

### 1. Variables
- **X (Inflation Rate)**: Percentage change in the general price level of goods and services over time.
- **Y (Unemployment Rate)**: Percentage of the labor force that is unemployed but actively seeking employment.

### 2. Research Objective
The relationship between inflation and unemployment is often seen as inversely correlated. However, the analysis investigates whether this holds true across the Eurozone and examines variations across countries and time periods.

### 3. Methods
- **Descriptive Statistics**: Summary statistics such as mean, standard deviation, minimum, and maximum values for both inflation and unemployment.
- **Regression Analysis**: Multiple regression models to explore how inflation affects unemployment, including fixed-effects models to control for country and year variations.
- **Visualizations**: Scatter plots with linear and quadratic fits to visually assess the relationship between the two variables. Trends are also plotted over time for each country.

## Results Overview

- **Linear Relationship**: The analysis shows a weak inverse relationship between inflation and unemployment (e.g., Phillips Curve) across the Eurozone, but with significant variations by country.
- **Quadratic Relationship**: The quadratic model reveals a more complex dynamic, where at lower inflation rates, unemployment tends to decrease, but higher inflation leads to increases in unemployment for some countries.
- **Country Comparisons**: A comparison of trends between major economies (e.g., France and Germany) and smaller economies (e.g., Greece) offers insights into how different fiscal policies impact inflation and unemployment.

## How to Use

1. Clone this repository.
2. Install the necessary R packages listed in the `Rmd` file.
3. Run the `DATA.Rmd` file to reproduce the analysis and visualizations.


## Visualizations

The project generates multiple visualizations to help understand the relationship between inflation and unemployment, including:
- Distribution of inflation and unemployment for all countries.
- Trend analysis of inflation and unemployment over the years.
- Scatter plots with linear and quadratic fits.

## Data Sources

- Inflation and unemployment data are obtained from publicly available Eurozone statistics databases (such as Eurostat).

## Conclusion

The project confirms that while there is an observable inverse relationship between inflation and unemployment, it is not consistent across all countries or time periods. The models suggest that other factors, including country-specific policies and economic conditions, play significant roles in shaping this relationship.

