# Unemployment Analysis with Python

## Overview

This project performs an exploratory data analysis (EDA) of unemployment trends in India using Python. The analysis focuses on regional unemployment patterns, monthly trends, the impact of the COVID-19 pandemic, and the relationships between key labour market indicators through statistical analysis and visualizations.

---

## Objective

Analyze unemployment data in India to identify regional and temporal trends, evaluate the impact of the COVID-19 pandemic on unemployment rates, and derive meaningful insights through exploratory data analysis.

---

## Dataset

The project uses the **Unemployment in India** dataset containing unemployment statistics across multiple Indian states and union territories.

### Features

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area (Rural/Urban)

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

1. Import Required Libraries
2. Dataset Loading
3. Data Cleaning and Preparation
4. Exploratory Data Analysis
5. Regional Analysis
6. Time-Series Analysis
7. COVID-19 Impact Analysis
8. Correlation Analysis
9. Dataset Summary
10. Key Insights
11. Conclusion

---

## Analysis Performed

- Data cleaning and preprocessing
- Missing value inspection
- Region-wise unemployment analysis
- Month-wise unemployment trend analysis
- Time-series comparison for major Indian states
- Top 10 states by average unemployment rate
- Correlation analysis of labour market indicators
- Pre-COVID vs. Post-COVID unemployment comparison

---

## Visualizations

The project includes the following visualizations:

- Top 10 States with Highest Average Unemployment Rate
- Monthly Average Unemployment Trend
- Time-Series Analysis of Major States
- Pre-COVID vs. Post-COVID Comparison
- Correlation Heatmap

---

## Key Insights

- Unemployment rates vary considerably across different Indian states.
- Monthly unemployment trends reveal significant fluctuations over time.
- The COVID-19 pandemic contributed to increased unemployment levels across the country.
- Labour participation and employment indicators exhibit meaningful relationships with unemployment rates.
- Regional analysis helps identify states that may require targeted employment policies and interventions.

---

## Project Structure

```text
DataScience-Task2-UnemploymentAnalysis
│
├── data
│   ├── .gitkeep
│   └── Unemployment in India.csv
│
├── notebooks
│   └── Unemployment_Analysis.ipynb
│
├── outputs
│   └── images
│       ├── top10_unemployment.png
│       ├── monthly_trend.png
│       ├── time_series_states.png
│       ├── covid_comparison.png
│       └── correlation_heatmap.png
│
└── README.md
```

---

## How to Run

1. Clone the repository.

2. Create and activate a Python virtual environment.

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Open:

```
DataScience-Task2-UnemploymentAnalysis/notebooks/Unemployment_Analysis.ipynb
```

5. Run all notebook cells sequentially.

---

## Future Improvements

- Perform predictive time-series forecasting of unemployment rates.
- Develop an interactive dashboard using Plotly or Streamlit.
- Incorporate additional socioeconomic indicators for deeper analysis.
- Build state-wise forecasting models for future unemployment trends.
