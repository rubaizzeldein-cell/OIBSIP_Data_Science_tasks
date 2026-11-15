# Task 3: Car Price Prediction

## Objective
The objective of this project is to analyze a used car dataset, clean the data, explore the relationships between various car features (like age, mileage, and fuel type), and prepare the data for building a machine learning model to predict car selling prices.

## Steps Performed
* **Data Cleaning:** Handled missing values by imputing numerical columns with the mean and categorical columns with the mode. Removed duplicates and standardized text formatting (e.g., lowercasing fuel and transmission types).
* **Feature Engineering:** Extracted the car `Brand` from the name and calculated `Car_Age` using 2024 as the baseline year. Dropped the original `name` and `year` columns.
* **Exploratory Data Analysis (EDA):** Visualized the distribution of selling prices, compared prices across different fuel types using boxplots, and examined the relationship between selling price and car age using scatter plots.
* **Feature Encoding:** Applied One-Hot Encoding to categorical variables (with `drop_first=True` to prevent multicollinearity), expanding the dataset features for machine learning.
* **Correlation Analysis:** Generated a correlation heatmap to analyze the relationships and dependencies between the numerical features.

## Tools Used
* **Python** (Programming Language)
* **Pandas & NumPy** (Data manipulation and preprocessing)
* **Seaborn & Matplotlib** (Data visualization)
* **Scikit-Learn** (Preprocessing and modeling framework)
* **Jupyter Notebook** (Development environment)

## Outcome
The dataset was successfully cleaned and enriched with new features (Brand and Car Age). Exploratory data analysis provided clear insights into price distributions and the negative correlation between car age and selling price. Finally, all categorical variables were numerically encoded, resulting in a fully preprocessed dataset with 364 features, perfectly primed for training predictive regression models.
