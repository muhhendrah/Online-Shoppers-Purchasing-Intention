# Online-Shoppers-Purchasing-Intention
---
*Tools : Python, Google Colab, Git, Numpy, Pandas, Scipy, Matplotlib, Seaborn, Scikit-Learn*

Data Source : [Online Shoppers Purchasing Intention](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)

Our company is an e-grocery startup that provides groceries products online. We came up by seeing the great potential of e-grocery data to produce a 36% increase in CR (2020 vs 2021) and of course, we can use this to generate profits through increased conversion rates. Moreover, a phenomenon that has emerged recently is the Start-up bubble with one of the causes: too much dependence on investors. So we need to think about how to make our e-commerce ecosystem profitable and survive in the rampant competition.

## Project Background
---
For now, our company only has a `15,63%` conversion rate in the whole year 2021. We have to increase the company's conversion rate up to 20% and gross profit up to 15% in 2023 by :
- Predict whether visitors will convert or not using predictive modeling
- Analyze the factors that affect the increase in conversion rate

## Exploratory Data Analysis
---
We have some interesting insights from the EDA, there are :
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

## Business Insights & Recommendation
---

Recommendations:
1. Prioritizing existing resources to improve, promote, and advertise in Kota Tangerang Selatan, Depok, and Jakarta for marketing purposes
2. Discount Offering to Real-Time Non-Purchase Predicted Visitors
3. Improving the UI/UX platform/website

With implementing the recommendations, our company has the potential to `increase the conversion rate from 15.63% up to 23.32% and increase the company’s gross profit up to 17%`.

---

Full Explanation : [Online Shoppers Purchasing Intention Prediction for Higher Conversion Rate using Machine Learning (E-Grocery Startup Case)](https://medium.com/@muhhendrah/online-shoppers-purchasing-intention-prediction-for-higher-conversion-rate-using-machine-learning-6765cb0fbad2)
