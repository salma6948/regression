📊 Scatter Matrix – Advertising Dataset Analysis
📌 Overview

This notebook performs exploratory data analysis (EDA) using a scatter matrix (pairplot) to study the relationships between advertising budgets and product sales.

The goal is to visually understand which advertising channels influence sales and how the variables interact with each other before building a predictive model.

📂 Dataset Description

The dataset contains the following variables:

TV – Advertising budget spent on TV (in thousands)

radio – Advertising budget spent on radio (in thousands)

newspaper – Advertising budget spent on newspapers (in thousands)

sales – Product sales (in thousands of units)

📈 What the Scatter Matrix Shows

The scatter matrix plots every variable against every other variable, allowing quick visual inspection of correlations.

Key observations:

TV vs sales → strong positive correlation

radio vs sales → moderate positive correlation

newspaper vs sales → weak or no correlation

Predictors (TV, radio, newspaper) are not strongly correlated with each other, reducing multicollinearity concerns

🎯 Purpose of This Analysis

Identify important predictors for sales

Check if linear regression is appropriate

Detect outliers or anomalies

Decide whether some variables should be removed or regularized

🧠 Conclusions

TV advertising is the most influential factor

Radio advertising has a noticeable impact

Newspaper advertising contributes little to no predictive power

Linear models are suitable for this dataset

🛠 Libraries Used

pandas

matplotlib

seaborn

🚀 Next Steps

Possible extensions:

Compute correlation coefficients numerically

Fit a linear regression model

Compare models with and without the newspaper feature

Apply regularization (Ridge / Lasso)
