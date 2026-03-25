# Data Science & Analytics Portfolio
Portfolio of data science and analytics projects covering e-commerce analytics, user behavior analysis, conversion optimization, statistical modeling, experimentation, and BI visualization.

Interactive BI dashboards can be found on [Xinyu Tableau Profile](https://public.tableau.com/app/profile/xinyu.xiang5112/vizzes)

## E-commerce Data Analytics & User Behavior Analysis
### [Taobao User Purchase Behavior Analysis (淘宝用户购买行为数据分析)](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/taobao%20user%20behavior%20analysis/%E6%B7%98%E5%AE%9D%E7%94%A8%E6%88%B7%E8%B4%AD%E4%B9%B0%E8%A1%8C%E4%B8%BA%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90.ipynb)

Analyzed **6.2 million** user behavior records (click, favorite, cart, purchase) across 31 days covering the **Double-12 shopping festival**. Built a full-stack e-commerce analytics pipeline: KPI metrics system (PV/UV/conversion rate/repurchase rate), multi-stage **conversion funnel**, **RFM user segmentation**, retention & repurchase analysis, and **promotion effectiveness attribution** with pre/during/post comparison. Identified category-level behavior paths and segment-specific promotion response patterns.

_Keywords: metrics system design, conversion funnel, RFM user segmentation, retention & repurchase analysis, promotion attribution, user behavior path analysis, e-commerce KPI monitoring_

_Tools: Python (Pandas, Numpy, Matplotlib)_

### [Xiaohongshu User Revenue Factor Analysis (小红书用户收入影响因素分析)](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/xiaohongshu%20user%20revenue%20analysis/%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%94%A8%E6%88%B7%E6%94%B6%E5%85%A5%E5%BD%B1%E5%93%8D%E5%9B%A0%E7%B4%A0%E5%88%86%E6%9E%90.ipynb)

Explored key drivers of user spending on Xiaohongshu (RED) platform using **multiple linear regression** on 29,000+ user records. Full modeling pipeline: data cleaning, **outlier detection (IQR)**, **feature engineering**, multicollinearity check (VIF), OLS/Ridge/Lasso model comparison with train/test split, **standardized coefficient analysis** for feature importance ranking, and **lifecycle × engagement user segmentation** for targeted operation insights.

_Keywords: regression modeling, feature engineering, outlier detection, multicollinearity diagnosis, model evaluation (R²/RMSE/MAE), user segmentation, standardized coefficient attribution_

_Tools: Python (Pandas, Numpy, Scikit-learn, Statsmodels, Seaborn, Matplotlib)_

### [ShopEasy Marketing Insights: Conversion, Engagement and Feedback](https://github.com/eggchoo/ShopEasy-marketing-analysis)

Analyzed e-commerce conversion funnel, user engagement metrics, and customer satisfaction ratings. Conducted **NLP sentiment analysis** on customer feedback to identify product and service improvement areas.

_Keywords: conversion analysis, engagement metrics, sentiment analysis, customer feedback mining_

_Tools: SQL Server, Python (Pandas, nltk), Power BI_

[Power BI dashboards: ShopEasy Marketing Insights](https://app.powerbi.com/links/ZRnbstLhCp?ctid=6f0bb72f-5377-4ddf-936a-b6c72bf21ae2&pbi_source=linkShare&bookmarkGuid=519eae8b-b62d-47ab-b44d-3dfc1c9fd223)

## User Retention, Churn & Lifecycle Analysis
### [OULAD User Retention, Churn & Conversion Analysis](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/OULAD%20project/OUTLAD_user_retention%20%26%20conversion_analysis.ipynb)

Built **lifecycle metrics framework** (activation, retention, churn, conversion). Identified at-risk users using **survival analysis** and quantified conversion drivers using **logistic regression** with covariate adjustment.

_Keywords: lifecycle metrics, retention/churn analysis, survival analysis, logistic regression, user risk profiling_

_Tools: Python (Lifelines, Statsmodels, Pandas, Numpy, Matplotlib, Seaborn)_

### [TelecomX Churn Analysis & Prediction](https://github.com/eggchoo/Telecom-customer-churn-analysis-and-prediction)

Identified key churn drivers, profiled high-risk user segments, and built a **Random Forest** classifier to predict future churners and inform targeted retention strategy.

_Keywords: churn prediction, user segmentation, Random Forest, feature importance, retention strategy_

_Tools: Python (Pandas, Numpy, Scikit-learn), Power BI_

[Power BI dashboards: TelecomX Churn Analysis & Prediction](https://app.powerbi.com/links/dV7FDMM88M?ctid=6f0bb72f-5377-4ddf-936a-b6c72bf21ae2&pbi_source=linkShare&bookmarkGuid=a8e6f4a7-8f13-4535-a8f2-f4912f82b294)

## Experimentation & A/B Testing
### [Marketing Campaigns: Funnel Analysis & A/B Testing](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/Marketing%20campaigns%20ab%20testing/marketing_campaign_ab%20testing.ipynb)

Diagnosed **funnel metrics** performance and measured conversion lift across experiment variants with experimental integrity checks and **Chi-square** hypothesis testing.

_Keywords: funnel analysis, A/B testing, hypothesis testing, conversion optimization, experiment design_

_Tools: Python (Statsmodels, Scipy, Pingouin, Pandas, Numpy, Matplotlib, Seaborn)_

### [CookieCats Game Retention: A/B Testing](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/cookie%20cats%20game%20retention%20ab%20testing/cookie_cats_ab_test_game_retention.ipynb)

Evaluated the impact of game design changes on early player retention with **SRM checks**, **Mann-Whitney U test**, and **two-proportion z-test** for statistical rigor.

_Keywords: A/B testing, causal inference, retention analysis, SRM validation, statistical significance testing_

_Tools: Python (Scipy, Pandas, Numpy, Matplotlib, Seaborn)_

## Data Mining & Industry Research
### [Teamfight Tactics In-Game Strategy Analysis](https://github.com/eggchoo/Data-Science-Insight-Portfolio-/blob/main/Teamfight%20Tactics%20combo%20clustering%20analysis/tft%20match%20analysis.ipynb)

Applied **K-means clustering** on competitive match data from top 100 Challenger players to discover high-performing strategy archetypes. Quantified strategy performance via placement, pick rate, Top-4 rate, and win rate metrics.

_Keywords: K-means clustering, unsupervised learning, strategy mining, performance metrics_

_Tools: Python (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn), Tableau_

[Tableau dashboards: Teamfight Tactics In-Game Strategy](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/TeamfightTacticscomboanalysis/traitsStats)

### [Yelp Business Insights](https://github.com/eggchoo/Yelp-business-analysis)

Analyzed large-scale Yelp data to identify drivers of business ratings, user engagement, and platform visibility using cloud-based data infrastructure.

_Keywords: large-scale data processing, cloud analytics, business driver analysis_

_Tools: Python, SQL (MySQL), AWS, Snowflake_

## BI Dashboards & Data Visualization
### [GlobalLink Logistics Performance](https://github.com/eggchoo/GlobalLink-Logistics-analysis/blob/main/README.md)

Built operational dashboards tracking delivery efficiency, return rates, and logistics KPIs to support data-driven business decisions.

_Keywords: KPI dashboard, operational metrics, logistics analytics_

_Tools: Power BI_

[Power BI dashboard: GlobalLink Logistics Performance](https://app.powerbi.com/links/nrEMu1Vy_7?ctid=6f0bb72f-5377-4ddf-936a-b6c72bf21ae2&pbi_source=linkShare)

### Tableau Dashboards

[Superstore Sales & Orders](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/Superstoresalesorders/overview) — Sales and order performance (2022-2024) with dynamic visualization tools.

[Superstore Product Subcategory Performance](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/tableexercise/Dashboard1) — Ranked subcategory analysis with YoY comparison and trend lines.

[Superstore Performance Overview](https://public.tableau.com/app/profile/xinyu.xiang5112/viz/Superstoretableau_17677705726460/overview) — KPI dashboard with direct YoY comparisons.
