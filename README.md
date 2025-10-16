# Business-Failure-Survival-Analysis
This project analyzes U.S. business stability by integrating FDIC bank failure data with BLS business survival data using Python. It identifies trends in failures, survival rates, and economic correlations to predict risks and support informed policy decisions.
Project Overview
This project conducts a comprehensive analysis of U.S. business stability by integrating Federal Deposit Insurance Corporation (FDIC) bank failure data with Bureau of Labor Statistics (BLS) business survival data. Using Python for data analysis, statistical modeling, and visualization, it identifies patterns in business failures, survival rates, and their economic correlations to help predict risks and inform policy decisions.

Objectives
•	Analyze Historical Trends: Examine U.S. bank failures and business survival rates from 2000–2025.
•	Identify Risk Factors: Explore geographic, temporal, and economic factors influencing business failures.
•	Predictive Modeling: Use regression analysis to model employment trends, survival rates, and economic impacts.
•	Simulate Interventions: Conduct "what-if" analyses to estimate the potential impact of improving business survival rates.

Dataset Sources
•	FDIC Failed Bank List:
o	Contains records of U.S. bank failures (name, location, certificate number, closing date).
o	FDIC Failed Bank List
•	BLS Business Employment Dynamics:
o	Tracks business survival rates, employment numbers, and establishment counts by cohort year.
o	BLS Business Dynamics
Tech Stack
•	Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn)
•	Jupyter Notebook for analysis and visualization
•	SQL-ready datasets for further querying and dashboard integration

Key Analyses Performed
1. Exploratory Data Analysis (EDA)
•	Bank failure trends by year and state
•	Business survival curves by cohort
•	Correlation between bank failures and 5-year business survival rates
2. Regression Modeling
•	Total employment prediction
•	Survival rate forecasting
•	Average establishment size modeling
•	Cohort-specific and economic cycle analyses
3. Geospatial & Temporal Insights
•	Top states with highest failure counts (GA, FL, IL, CA, MN)
•	Impact of financial crises (2008–2010 accounted for 56.3% of all failures)
4. Predictive “What-If” Analysis
•	Simulated impact of survival rate improvements (e.g., +5% survival → +17,014 businesses saved for the 2015 cohort)

Key Insights
•	Peak Failure Year: 2010 saw 157 bank failures during the financial crisis.
•	Survival Rates: Only ~50% of businesses survive past 5 years (2019 cohort: 51.6%).
•	Employment Trends: Average employment per establishment grows from 5.2 at startup to 13.2 after 10 years.
•	Correlation: Moderate positive correlation (r = 0.305) between bank failures and 5-year business survival rates.

