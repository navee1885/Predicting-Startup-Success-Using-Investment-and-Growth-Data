Predicting Startup Success Using Investment & Growth Data
Project Overview

This project explores how investment, industry, and geographic factors influence the growth rate of startups. Using a real-world dataset of 5,000 startups, the goal is to identify key growth drivers, analyze funding patterns, and build machine learning models to predict startup success.

Predicting-Startup-Success-Usin…

Objectives
Identify key factors affecting startup growth
Analyze investment, valuation, and industry trends
Build predictive ML models for growth rate forecasting
Provide recommendations for investors and founders

Predicting-Startup-Success

Dataset Summary
Attribute	Description
Source	Kaggle Startup Investment Dataset
Records	5,000 startups
Features	Industry, Country, Funding Rounds, Investment, Valuation, Number of Investors, Founded Year
Target Variable	Growth Rate (%)
Data Quality	No missing values

Predicting-Startup-Success
Tools & Technologies

Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Scikit-learn
ML Models: Linear Regression, Random Forest, Gradient Boosting, SVM
Evaluation Metrics: R², MSE, MAE
Best model: Gradient Boosting (R² = 0.0004) — low predictive power due to weak feature relationships


Predicting-Startup-Success

Key Insights
Startup Growth & Investment Trends

Strong positive correlation between valuation and total investment

EdTech is the fastest-growing industry, followed by FinTech

Growth Rate peaks at funding round 6

Germany and USA show the highest growth rates geographically

Average growth rate across all startups: 102.1%

Weak Relationships

Little to no correlation between growth rate and:

Number of investors

Year founded

Total investment

Startup valuation

Indicates that growth is influenced by external/qualitative factors like product, market timing, founder expertise


Predicting-Startup-Success-Usin…

Modeling Results
Model	R² Score	MAE	MSE
Gradient Boosting (Best)	0.0004	0.6259	0.5939
Random Forest	0.0001	0.6412	0.6145
Linear Regression	0.0000	0.6583	0.6321

Models struggled to explain growth — meaning startup success is not purely numerical.

Predicting-Startup-Success-Usin…

Business Recommendations
Strategy	Description
Product Diversification	Expand product offerings to reduce dependency on a single revenue stream
Market Expansion	Enter new geographies or target new customer segments
Strategic Acquisitions	Acquire smaller companies to access technology or new markets
Data-Driven Monitoring	Use Tableau dashboards for real-time investor decision-making

Predicting-Startup-Success-Usin…

Conclusion

Investment strongly impacts valuation, but not necessarily growth rate

Industry and geography are stronger predictors of success than funding volume

Machine Learning provides directional insights, but current features do not fully explain startup success

Future improvements: add qualitative data (team experience, product type, revenue, customer churn) for higher prediction accuracy
