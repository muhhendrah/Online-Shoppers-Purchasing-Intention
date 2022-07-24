# Online-Shoppers-Purchasing-Intention
---
Data Source : [Online Shoppers Purchasing Intention](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)

Lauk Fresh is a B2C e-grocery startup that provides groceries products online. We came up by seeing the great potential of e-grocery data to produce a 36% increase in CR (2020 vs 2021) and of course, we can use this to generate profits through increased conversion rates. Moreover, a phenomenon that has emerged recently is the Start-up bubble with one of the causes: too much dependence on investors. So we need to think about how to make our e-commerce ecosystem profitable and survive in the rampant competition.

## Project Background
---
Lauk Fresh only has a `15,63%` conversion rate in the whole year 2021. We have to increase the company's conversion rate up to 20% and gross profit up to 15% in 2023 by :
- Predict whether visitors will convert or not using predictive modeling
- Analyze the factors that affect the increase in conversion rate

## Exploratory Data Analysis
---
Lauk Fresh have some interesting insights from the EDA, there are :
- Direct visits and google organic dominate the 18 types of traffic, it shows that visitor intentions and recommendations from google are still very relevant.
- Majority of our visitors come from big cities and the top 3 are South Tangerang, Depok, and Jakarta.
- The top 4 factors that affect the conversion rate are Exit Rates, Number of Administrative Pages, Product Related Pages Duration, and Number of Product Related Pages.

## Data Preprocessing
---
- Handling Duplicate Value
- Feature Encoding
- Data Transformation
- Outlier Handling
- Feature Selection
- Imbalance Target Handling

## Modeling
---
10 Models are tested with F2 Score as Evaluation Target with 0 value as a positive label to reduce False Negatives without completely ignoring the False Positives. Turns out the smallest False Negative goes to the `Light Gradient Boosting Machine - Hyperparameter Tuning model with 6.67% and 90.6% F2 Score with using only the top 4 predictors (Exit Rates, Administrative Pages, Product Related Pages Duration, and Product Related Pages)`.

The final model will be used as decision support to offer discount to non-purchase predicted visitors with the following workflow.

![Model Workflow](https://github.com/muhhendrah/Online-Shoppers-Purchasing-Intention/blob/main/images/Model-Implementation-Workflow.png)

## Business Insights & Recommendation
---
Based on the EDA and modeling we have done, we do the Root Cause Analysis and Sensitivity Analysis to help us to identify the fundamental problems and drive the optimal solutions.

![Root Cause Analysis](https://github.com/muhhendrah/Online-Shoppers-Purchasing-Intention/blob/main/images/Root-Cause-Analysis.png)

![Sensitivity Analysis(1)](https://github.com/muhhendrah/Online-Shoppers-Purchasing-Intention/blob/main/images/Sensitivity-Analysis(1).png)

![Sensitivity Analysis(2)](https://github.com/muhhendrah/Online-Shoppers-Purchasing-Intention/blob/main/images/Sensitivity-Analysis(2).png)

Recommendations (Further recommendations explained in Final Presentation Deck):
1. Discount Offering to Real-Time Non-Purchase Predicted Visitors
2. Decrease 15% Exit Rates
3. Increase 5% Administrative
4. Increase 5% Product Related Duration
5. Decrease 10% Product Related

With implementing all of those recommendations, Lauk Fresh has the potential to `increase conversion rate by 14.77% and increase gross profit by 95%`.
