# Task 2: Unemployment Analysis with Python

## Objective
The objective of this project is to analyze and visualize the unemployment landscape in India, exploring regional differences, temporal trends, correlation among labor market indicators, and the specific impact of the COVID-19 pandemic.

## Steps Performed
* **Data Cleaning & Preparation:** Loaded the dataset, stripped whitespaces from column names and string fields, removed rows with missing values, converted date strings into datetime objects, and sorted the records chronologically.
* **Exploratory Data Analysis (EDA):** Generated descriptive statistics to summarize the distributions of the unemployment rate, total employment, and labor participation rate.
* **Regional Analysis:** Grouped the data by region to calculate and visualize the top 10 states with the highest average unemployment rates using bar charts.
* **Temporal Trend Analysis:** Plotted time-series line charts for the overall average unemployment rate over time and compared specific states (Delhi, Kerala, and West Bengal) to track fluctuations.
* **Correlation Analysis:** Created a heatmap to examine the relationships between the estimated unemployment rate, estimated employment count, and labor participation rate.
* **COVID-19 Impact Assessment:** Segmented the dataset into "Pre-COVID" and "COVID period" (starting March 2020) to quantitatively compare labor metrics before and during the pandemic.

## Tools Used
* Python
* Pandas & NumPy (Data manipulation)
* Seaborn & Matplotlib (Data visualization)
* Jupyter Notebook

## Outcome
The analysis successfully mapped labor market trends, highlighting severe regional disparities where states like Tripura and Haryana experienced the highest average unemployment. Time-series visualizations and monthly breakdowns revealed a sharp, substantial spike in unemployment during April and May 2020. By comparing the segmented data, the analysis confirmed that the average unemployment rate nearly doubled from 9.50% pre-COVID to 17.77% during the COVID-19 period, accompanied by a noticeable decline in the labor participation rate[cite: 12].
