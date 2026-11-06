# ChurnQuest – Customer Churn Analysis

## 1. Project Overview

ChurnQuest is a customer churn analysis project focused on identifying factors associated with customer attrition at Airtel, a telecommunications company.

The objective was to analyse customer behaviour, identify patterns associated with churn, develop a statistical model to estimate churn likelihood, segment customers based on usage patterns, and assess the potential financial impact of customer attrition.

## 2. Project Objectives

- Identify key factors influencing customer churn.
- Analyse customer usage patterns and service preferences.
- Develop a logistic regression model to examine churn likelihood.
- Apply K-means clustering to identify distinct customer segments.
- Investigate interaction effects between selected variables.
- Evaluate the financial impact of churn through revenue and customer lifetime value analysis.
- Provide actionable business recommendations to improve customer retention.

## 3. Dataset Overview

- Total customer records: 5,000
- Customers who churned: 885
- Customers who did not churn: 4,115
- Overall churn rate: 17.70%

The dataset contains customer demographic information, account characteristics, service subscriptions, call usage and associated charges.

## 4. Tools and Technologies

**Tools**
- Microsoft Excel
- Jamovi

**Analytical Techniques**
- Descriptive and exploratory data analysis
- Pivot table analysis
- Correlation analysis
- Linear regression
- Logistic regression
- K-means clustering
- Chi-square and likelihood ratio tests
- Interaction effects analysis
- Revenue impact and customer lifetime value analysis
- Time-series and seasonal analysis

## 5. Key Areas of Analysis

### 5.1 Exploratory Data Analysis

Examined customer characteristics, service subscriptions, usage patterns and differences between customers who churned and those who remained.

### 5.2 Statistical Analysis

Used correlation, regression and statistical significance tests to investigate relationships between customer behaviour and churn.

### 5.3 Logistic Regression

Developed a logistic regression model to examine the relationship between customer attributes, service usage and the likelihood of churn.

The analysis included predictor coefficients, odds ratios, confidence intervals, significance tests and interaction effects.

### 5.4 Customer Segmentation

Applied K-means clustering to standardised customer usage variables to identify distinct customer segments.

Both K=3 and K=4 clustering solutions were explored in response to separate analytical questions. Churn rates were subsequently compared across the resulting customer segments.

### 5.5 Interaction Effects

Investigated whether the relationship between international plan subscriptions and churn varied with international calling minutes.

### 5.6 Financial Impact Analysis

Estimated revenue associated with churned customers and evaluated potential revenue losses over an assumed customer lifetime.

### 5.7 Seasonal Analysis

Explored seasonal churn patterns using constructed date information.

The generated dates are for analytical demonstration and should not be interpreted as actual historical customer transaction dates.

## 6. Selected Analysis and Visualisations

### 6.1 Monthly Customer Churn Analysis

![Monthly Customer Churn Analysis](Screenshots/Yearly%20Churn%20Rate.png)

Compared monthly customer churn patterns across 2024 and 2025 to explore potential seasonal variations.

*Note: The dates used for this analysis were constructed for demonstration purposes.*

### 6.2 Customer Service Calls and Churn

![Customer Service Calls and Churn](Screenshots/Customer%20Service%20Calls%20Churn.png)

Examined the distribution of churned and retained customers across different customer service call frequencies.

The analysis helps investigate whether repeated customer service interactions are associated with customer attrition.

### 6.3 Evening Calling Behaviour and Churn

![Evening Calls and Churn](Screenshots/Evening%20Calls%20Churn.png)

Examined customer churn rates across different evening calling ranges to identify potential relationships between calling behaviour and customer retention.

### 6.4 International Plan and Customer Churn

![International Plan and Churn](Screenshots/International%20Plan%20Churn.png)

Customers with an international plan recorded a churn rate of 41.65%, compared with 15.20% among customers without an international plan.

This represents a substantial difference in observed churn rates and identifies international plan subscribers as a segment requiring further investigation.

### 6.5 Customer Segmentation Using K-means

![K-means Customer Segmentation](Screenshots/Cluster%20wise%20Churn.png)

Applied K-means clustering to standardised customer usage variables and compared churn distributions across customer segments.

Both three-cluster and four-cluster solutions were examined for their respective analytical objectives.

### 6.6 Logistic Regression and Interaction Effects

![Logistic Regression Analysis](Screenshots/Logistic%20Regression%20Churn.png)

Developed a logistic regression model to investigate factors associated with customer churn.

The analysis examined:
- Regression coefficients and odds ratios.
- Statistical significance of individual predictors.
- Confidence intervals.
- Interaction between international plan subscriptions and international calling minutes.
- Interaction between international plan subscriptions and customer service calls.

## 7. Key Business Insights

The analysis identified several important observations:

- International plan subscribers exhibited a substantially higher observed churn rate than non-subscribers.
- Customers who churned made more customer service calls on average than retained customers.
- Churned customers recorded higher average daily calling minutes and associated charges.
- Voice mail plan subscribers exhibited a lower observed churn rate than customers without the plan.
- Customer segments displayed different churn distributions.
- Customer attrition represents a potential source of recurring revenue loss.

These findings can help Airtel investigate customer dissatisfaction, review service offerings and prioritise retention initiatives.

## 8. Business Recommendations

Based on the analysis, the following recommendations are proposed:

1. **Review international plan offerings:** Investigate pricing, service quality and customer expectations among international plan subscribers.
2. **Improve customer service:** Identify customers with repeated service interactions and introduce proactive complaint resolution.
3. **Develop targeted retention strategies:** Prioritise customer segments exhibiting relatively higher churn rates.
4. **Review service packages:** Evaluate whether existing plans adequately meet customer usage requirements.
5. **Monitor churn indicators:** Use customer usage patterns and statistical model outputs to support customer retention initiatives.
6. **Protect recurring revenue:** Prioritise retention initiatives based on potential revenue impact.

## 9. Project Limitations

- The analysis is based on a dataset of 5,000 customer records.
- Statistical associations do not necessarily establish causation.
- The seasonal analysis uses constructed dates rather than verified historical dates.
- Customer lifetime revenue estimates depend on assumptions about customer retention and revenue stability.
- Clustering results depend on the selected variables and number of clusters.
- The findings should be interpreted within the limitations of the available dataset.

## 10. Project Deliverable

The complete Excel workbook contains the analysis, supporting datasets, calculations, pivot tables, charts and results.

**Main file:** `Prajot_Tele_ChurnQuest.xlsx`

---

**Project by:** Prajot Manohar Ghaywat

**Domain:** Data Analytics | Customer Churn | Statistical Analysis | Business Insights