# Raunak-Sharma-Portfolio
This portfolio highlights my contributions to Swire Coca-Cola’s predictive maintenance project, including EDA, data preprocessing, feature engineering, and predictive modeling using algorithms like XGBoost. It demonstrates expertise in machine learning, data visualization, and advanced analytics.

# Swire Coca-Cola

## Table of Contents
1. [Project Overview](#project-overview)
2. [Business Problem](#business-problem)
3. [Project Objective](#project-objective)
4. [Solution](#solution)
5. [Contribution](#contribution)
6. [Business Value](#business-value)
7. [Challenges Encountered](#challenges-encountered)
8. [Learnings](#learnings)


## Project Overview
Swire Coca-Cola operates six production plants and produces over 192 million cases annually. However, due to unforeseen mechanical failures and maintenance issues, the company experiences significant downtime, leading to production shortfalls. 

## Business Problem
Unplanned machine downtimes at Swire Coca-Cola plants cost the company approximately $60 million annually. These downtimes disrupt production, lead to missed delivery deadlines, and increase overall operational costs.

## Project Objective
This project aims to provide Swire Coca-Cola with a predictive maintenance framework that may help minimize unplanned machine downtimes, improve productivity, and reduce financial losses across their production plants. Focusing on **ACTUAL_WORK_IN_MINUTES** (downtime), which represents machine downtime duration, the analysis seeks to predict maintenance needs and inform preventive measures.

## Solution
Our group conducted exploratory data analysis (EDA) to uncover patterns, visualize trends, and handle missing data, ensuring a reliable dataset for modeling. We increased the sample size, engineered new features, and tested multiple regression algorithms, including Linear Regression, Random Forest, Gradient Boosting, and XGBoost. While XGBoost emerged as the best-performing model with an R² of 0.49, its moderate performance led us to develop a Break-Even Analysis to provide actionable recommendations for maintenance planning and cost reduction. This combined approach offered a comprehensive framework to predict and manage downtimes, improve productivity, and reduce financial losses for Swire Coca-Cola.

## Contribution
I focused on exploratory data analysis (EDA), addressing missing values in critical columns like ACTUAL_WORK_IN_MINUTES and EQUIP_START_UP_DATE, and uncovering patterns through detailed analysis, data visualizations, and summarized tables. I experimented with various models, including Linear Regression, Random Forest, Gradient Boosting, and XGBoost, ultimately refining and optimizing the XGBoost model for downtime prediction. My responsibilities included feature engineering, hyperparameter tuning, debugging, and ensuring smooth execution of the modeling process. Additionally, I compiled the final notebook for both the EDA and modeling assignments, integrating key insights and results into a cohesive framework. This experience enhanced my technical expertise in machine learning, data visualization, and predictive analytics while addressing real-world challenges in predictive maintenance.

## Business Value
1. **Cost Optimization**:
   - Provided actionable insights to balance planned and unplanned maintenance costs.
2. **Operational Scalability**:
   - Delivered a framework for applying similar analyses to other functional locations.
3. **Enhanced Productivity**:
   - Provided recommendations to reduce machine downtime and improve operational efficiency.
4. **Proactive Maintenance**:
   - Enabled Swire Coca-Cola to anticipate failures and address them proactively.
5. **Resource Optimization**:
   - Improved resource allocation and scheduling across production plants.
6. **Improved Decision-Making**:
   - Empowered management with actionable insights and reliable predictions.

## Challenges Encountered

### Challenges Faced
1. **Data Quality Issues**:
   - Missing values in key columns like `ACTUAL_WORK_IN_MINUTES` and `EQUIP_START_UP_DATE`.
2. **Data Size**:
   - The dataset contained over 1.4 million rows, causing computational inefficiencies.
3. **Model Performance**:
   - The best-performing model, **XGBoost**, achieved moderate predictive accuracy with an R² of 0.49.
4. **Assumptions in Financial Data**:
   - Lack of real-world cost data required reliance on assumptions for break-even analysis.

### How We Overcame Them
1. **Data Quality Issues**:
   - Addressed missing values through imputation and focused on essential features.
2. **Data Size**:
   - Processed the dataset in chunks to improve efficiency.
3. **Model Performance**:
   - Augmented the predictive analysis with break-even analysis to provide actionable insights despite the moderate model performance.
4. **Assumptions in Financial Data**:
   - Used reasonable assumptions and created a calculator to allow for scenario-based adjustments.

## Learnings
1. **Data Engineering**:
   - Improved skills in handling large datasets and addressing missing values.
2. **Model Development**:
   - Gained experience in building and evaluating regression models, particularly **XGBoost**.
3. **Cost Analysis**:
   - Learned to apply break-even analysis for actionable business recommendations.
4. **Team Collaboration**:
   - Enhanced ability to work collaboratively and align team objectives effectively.
5. **Adaptability**:
   - Developed solutions to address moderate model performance using complementary analytical tools.
6. **Business Insight**:
   - Strengthened understanding of how data analysis impacts operational decision-making.
7. **Problem-Solving**:
   - Learned to tackle computational challenges and manage team objectives effectively.
8. **Business Context Application**:
   - Developed skills in applying predictive models to real-world problems and delivering actionable insights.

