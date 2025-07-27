LifelineInsight – Suicide Rate Analysis in India

This project aims to analyze and predict suicide trends in India using publicly available data. It provides **two versions** of analysis:

1. Regular Python-based Analysis (with Linear Regression)
The Python version performs exploratory data analysis and applies Linear Regression to predict suicide trends in India up to the year 2023.

Using the Kaggle dataset (2001–2012), we processed the data with Pandas, visualized key patterns using Seaborn/Matplotlib, and built a basic predictive model with Scikit-learn.

Key Steps:
- Data cleaning & preprocessing (handling nulls, filtering relevant columns)
- Year-wise suicide count visualization (line charts, bar plots)
- Gender-wise and age-group distribution analysis
- Predictive modeling with Linear Regression to estimate suicide counts for 2013–2023

File: LifelineInsight/Analysis_of_Suicide_Rate_India.ipynb

2. Tableau Dashboard for interactive data visualization
An interactive Tableau dashboard was built using the original Kaggle dataset to explore trends in suicide rates across gender, age groups, causes, and states.

Key Visuals:
- Gender-wise suicide trend (Dual line chart)
- Age group-wise distribution
- Top causes of suicide (Treemap)
- Geographical distribution (Map)
- Total suicides over the years

File: `Tableau_Dashboard/India_Suicide_Insights.twbx`

🔗View on Tableau Public: https://public.tableau.com/app/profile/sri.kadiyala/viz/IndiaSuicideInsights/IndiaSuicideInsights?publish=yes
