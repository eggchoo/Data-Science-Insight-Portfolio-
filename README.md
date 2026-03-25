# Data Science & Analytics Portfolio 
Portfolio of data science and analytics projects that I completed covering experimentation, causal inference, statistical modeling, machine learning, BI visualization and self-service analysis tools. 

Interactive BI dashboards can be found on [Xinyu Tableau Profile](https://public.tableau.com/app/profile/xinyu.xiang5112/vizzes) 

## Unsupervised Learning & Strategy Analytics
### [Teamfight Tactics In-Game Strategy Analysis](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/Teamfight%20Tactics%20combo%20clustering%20analysis/tft%20match%20analysis.ipynb) 

Used **K-means clustering** on patch 6.5 match data from top 100 NA Challenger players to identify high-performing **trait-based combos** and in-game strategies. Evaluated their impact on player outcomes: **placement, pick rate, Top-4 rate, and win rate** which supports strategic decision-making.

_Methods: EDA, K-means clustering_ 

_Tools: Pandas, Numpy, Scikit-learn, ast, json, Matplotlib, Seaborn, Tableau_

[Tableau dashboards: Teamfight Tactics In-Game Strategy](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/TeamfightTacticscomboanalysis/traitsStats) 

## Retention, Churn & Conversion
### [OUTLAD User Retention, Churn & Conversion Analysis](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/OULAD%20project/OUTLAD_user_retention%20%26%20conversion_analysis.ipynb) 

Developed **lifecycle metrics (activation, retention, churn, conversion)**. Identified at-risk users using survival analysis and conversion drivers using logistic regression with covariate adjustment.

_Methods: EDA, survival analysis, logistic regression_ 

_Tools: Lifelines, Statsmodels, Pandas, Numpy, Matplotlib, Seaborn_

## Experimentation & Casual Inference 
### [CookieCats Game Retention: A/B Testing](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/cookie%20cats%20game%20retention%20ab%20testing/cookie_cats_ab_test_game_retention.ipynb) 

Evaluated the impact of gate placement on early player retention with experimental integrity and SRM checks. 

_Methods: A/B testing, casual inferences, Mann-Whitney U test, Two-proportion z test_ 

### [Marketing Campaigns: Funnel Analysis & A/B testing](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/Marketing%20campaigns%20ab%20testing/marketing_campaign_ab%20testing.ipynb) 

Diagnosed funnel metrics performances and conversion differences across experiment variants with experimental integrity checks and Chi-square testing. 

_Methods: Funnel analysis, A/B testing, casual inferences_ 

_Tools: Statsmodels, Scipy, Pingouin, Pandas, Numpy, Matplotlib, Seaborn_

## Supervised learning & Predictive Modeling 
### [TelecomX Churn Analysis & Prediction](https://github.com/eggchoo/Telecom-customer-churn-analysis-and-prediction) 

Identified key churn drivers, profiled high-risk segments, and built a Random Forest model to predict future churners and inform retention strategy.

_Methods: EDA, supervised learning, predictive modeling, randomforest_ 

_Tools: Pandas, Numpy, Scikit-learn, Power BI_ 

[Power BI dashboards: TelecomX Churn Analysis & Prediction](https://app.powerbi.com/links/dV7FDMM88M?ctid=6f0bb72f-5377-4ddf-936a-b6c72bf21ae2&pbi_source=linkShare&bookmarkGuid=a8e6f4a7-8f13-4535-a8f2-f4912f82b294)

## E-commerce & User Behavior Analytics
### [Taobao User Purchase Behavior Analysis (淘宝用户购买行为数据分析)](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/taobao%20user%20behavior%20analysis/%E6%B7%98%E5%AE%9D%E7%94%A8%E6%88%B7%E8%B4%AD%E4%B9%B0%E8%A1%8C%E4%B8%BA%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90.ipynb)

Analyzed **6.2 million** user behavior records (click, favorite, cart, purchase) across 31 days covering the **Double-12 shopping festival**. Built conversion funnels, RFM user segmentation, retention/repurchase analysis, and promotion effectiveness evaluation with before/during/after comparison.

_Methods: EDA, conversion funnel analysis, RFM segmentation, retention & repurchase analysis, promotion A/B comparison, user behavior path analysis_

_Tools: Pandas, Numpy, Matplotlib_

### [Xiaohongshu User Revenue Regression Analysis (小红书用户收入影响因素分析)](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/xiaohongshu%20user%20revenue%20analysis/%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%94%A8%E6%88%B7%E6%94%B6%E5%85%A5%E5%BD%B1%E5%93%8D%E5%9B%A0%E7%B4%A0%E5%88%86%E6%9E%90.ipynb)

Explored key drivers of user spending on Xiaohongshu (RED) platform using **multiple linear regression** on 29,000+ user records. Performed outlier detection, user segmentation, multicollinearity checks (VIF), and model comparison (OLS, Ridge, Lasso) with train/test evaluation.

_Methods: EDA, OLS/Ridge/Lasso regression, feature engineering, outlier detection (IQR), user segmentation, standardized coefficient analysis_

_Tools: Pandas, Numpy, Scikit-learn, Statsmodels, Seaborn, Matplotlib_

## Product & Business Analytics
### [ShopEasy Marketing Insights: Conversion, Customer Engagement and Feedback](https://github.com/eggchoo/ShopEasy-marketing-analysis)

Analyzed conversion, engagement, and customer ratings; conducted sentiment analysis on customer feedback.

_Tools: SQL server, Pandas, nltk, Power BI_ 

[Power BI dashboards: ShopEasy Marketing Insights: Conversion, Customer Engagement and Feedback](https://app.powerbi.com/links/ZRnbstLhCp?ctid=6f0bb72f-5377-4ddf-936a-b6c72bf21ae2&pbi_source=linkShare&bookmarkGuid=519eae8b-b62d-47ab-b44d-3dfc1c9fd223)

### [GlobalLink Logistics Performance](https://github.com/eggchoo/GlobalLink-Logistics-analysis/blob/main/README.md) 

Provided data-driven insights to improve delivery efficiency, reduce return rates, and enhance overall business performance.

_Tools: Power BI_ 

[Power BI dashboard: GlobalLink Logistics Performance](https://app.powerbi.com/links/nrEMu1Vy_7?ctid=6f0bb72f-5377-4ddf-936a-b6c72bf21ae2&pbi_source=linkShare)

### [Yelp Buiness Insights](https://github.com/eggchoo/Yelp-business-analysis) 

Analyzed large-scale Yelp data to identify drivers of ratings, engagement, and business visibility. 

_Tools: Python, AWS, SNOWFLAKE (Python, MySQL)_  

## Data visualization and self-service BI dashboards 
### Tableau 

[Superstore Sales & Orders](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/Superstoresalesorders/overview) 

Sales and order performance (2022–2024) with dynamic visualization tools. 

[Superstore Product Subcategory performance](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/tableexercise/Dashboard1) 

Ranked subcategory analysis with YoY (year over year) comparison and trend lines. 

[Superstore Performance Overview](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/Superstoretableau_17677705726460/overview) 

KPI dashboard with direct YoY comparisons. 



