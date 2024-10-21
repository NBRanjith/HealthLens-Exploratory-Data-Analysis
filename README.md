
# HealthLens: Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) project focused on health care data. The aim of this project is to uncover patterns, insights, and trends from the dataset, and to provide a better understanding of the underlying structure of the data.

# Project Overview
The project covers the following steps:

1. Data Cleaning: Handling missing values, duplicates, and formatting issues.
2. Data Visualization: Using visual tools to explore distributions, correlations, and relationships.
3. Statistical Analysis: Analyzing key metrics, such as averages, proportions, and outliers.
4. Feature Engineering: Creating new features that provide deeper insights into the dataset.
Technologies Used

# Technologies Used

- Python: The primary language for data manipulation and analysis.
- Pandas: For data manipulation and handling.
- Matplotlib & Seaborn: For data visualization.
- Google Colab and Jupyter Notebook: For creating an interactive and readable analysis.

# Key Code and Findings
1. Data Cleaning
The dataset underwent extensive data cleaning, including:

- Removing null values.
- Converting categorical variables into numerical representations.
- Handling outliers by applying transformations where necessary.
### Key Finding: 
Approximately 15% of the dataset had missing values, which were either imputed using median values or dropped based on domain-specific knowledge.

## 2. Visualization
Visualizations played a critical role in understanding trends. Key charts include:

- Histograms: Displayed the distribution of patient ages, showing a higher frequency of certain age groups accessing healthcare services.
- Correlation Heatmap: Highlighted relationships between various health indicators and patient outcomes.
### Key Finding: 
There was a strong positive correlation (r = 0.76) between the age of patients and certain chronic conditions, showing that older patients are more prone to these conditions.

## 3. Statistical Insights
Several statistical techniques were applied to summarize the data:

- Descriptive Statistics: Mean, median, and standard deviation for key health metrics.
- Hypothesis Testing: Comparing health outcomes across different demographics (e.g., gender, age groups) using t-tests and ANOVA.
### Key Finding: 
 Female patients were found to have slightly better health outcomes across multiple categories compared to male patients, with statistical significance (p < 0.05).

 ## 4.  Feature Engineering
New features were created based on the available data:

- Risk Score: A composite health risk score was calculated by combining various health indicators like BMI, cholesterol levels, and blood pressure.
### Key Finding: 
 Patients with higher risk scores had a significantly higher chance of developing chronic illnesses, which can be useful for early intervention strategies.

 # Results
The EDA provides key insights into the healthcare dataset, such as:

- Key Trends: Overview of trends in the data, including age-based health outcomes.
- Correlations: Strong correlations between chronic conditions and health indicators.
- Visualizations: Various charts, including histograms and heatmaps, for deeper insights.

