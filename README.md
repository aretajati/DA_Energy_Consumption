# Energy Building Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the usage performance of energy utilities (water, gas, and electricity) within some countries in the USA. By analyzing various aspects of the consumption and cost, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the energy's performance.

![Screenshot 2024-09-23 101200](https://github.com/user-attachments/assets/2a364f75-b883-44bc-a4e1-430463335ab3)


### Business Requirement

The business requirement for this project is to analyze energy consumption and costs (water, gas, and electricity) across cities and buildings in the USA. It aims to track usage and related costs to identify inefficiencies, optimize performance, and provide data-driven recommendations. The project will offer city and building-level insights, highlight trends, and deliver clear visualizations and reports for informed decision-making on energy usage and cost reduction.

### KPI's Requirements
- Total Energy Consumption (Water in Litre, Gas in m3, and Electricity in KWh/m2).
- Total Energy Cost for each energy use ($).
- Total City.
- Total Building.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "Wemart_grocery_data.csv" file, containing detailed information about each sale made by the company.

### Tools

- Excel - Data Cleaning
  - [Download here](https://microsoft.com)
- SQL Server - Data Analysis
- PowerBI - DAX Calculation and Creating reports


### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- Data Cleaning and Preprocessing: Ensure data on energy consumption (water, gas, electricity) and costs are clean, consistent, and free of missing values. Convert units where necessary (e.g., liters, cubic meters, kWh) to maintain uniformity across datasets.

- Descriptive Statistics: Calculate basic statistics (mean, median, std. deviation) for energy consumption and costs across cities and buildings to understand central tendencies and spread.

- Energy Consumption Distribution: Analyze the distribution of water, gas, and electricity consumption by city and building. Identify any outliers or anomalies that indicate unusual usage patterns.

- Cost Analysis: Investigate the distribution of energy costs across different cities and buildings. Explore correlations between energy usage and cost to detect inefficiencies or high-cost areas.

- City and Building-Level Comparisons: Perform comparisons between cities and buildings for total energy consumption and costs. Identify regions or buildings that perform better or worse than others.

- Trend Analysis: Identify historical or time-based trends in energy consumption and costs to understand seasonal variations or patterns in energy use.

- Visualization: Create plots (e.g., bar charts, histograms, line graphs) to visually represent energy consumption and cost trends across cities, buildings, and time periods.
	
### Data Analysis

Include some interesting code/features worked with SQL, DAX expressions, and PowerBI dashboard.

### Results/Findings

- The analysis covers the period from January 2016 to June 2019 and includes 11 buildings across 5 U.S. cities: New York, Los Angeles, Chicago, Houston, and Phoenix.
- Water consumption is the highest among all utilities, followed by electricity, with gas being the least consumed.
- Despite lower consumption, gas costs are higher than electricity.
- Gas and electricity costs steadily increase over time, while water costs fluctuate, possibly due to changes in pricing or usage patterns.
- New York, Chicago, and Los Angeles are the top three cities in terms of utility consumption, but each has data from 3 buildings, while Phoenix and Houston only have 1 building each. This makes energy consumption comparisons across cities less conclusive.

### Recommendations

Based on the analysis, we recommend the following actions:
- Collect data from a more balanced number of buildings across all cities to ensure fair and accurate comparisons.
- Extend the analysis period to gather more data over time, providing a more comprehensive view of consumption trends.
- Investigate the factors driving fluctuating water costs, such as potential seasonal usage patterns or price variations. This is important for extensive analysis!
- Analyze potential energy-saving opportunities, particularly for gas, where costs are high despite lower consumption.
- Consider segmenting data by building type or size to account for variations in energy usage patterns, providing more targeted insights.

### Limitations

- The data and company name are unrelated and are solely used for a dummy project.
- The home, FAQ, and refresh buttons are not yet to be referred. However, in real projects where the pages are related to one another, these 3 buttons are necessary to be set and work as they are.


### References

1. SQL for Data Analysis by Cathy Tanimura.
2. [Stack Overflow](https://stack.com)


Feel free to see the interactivity of this dashboard by clicking the Electricity, Gas, or Water buttons. 😄
