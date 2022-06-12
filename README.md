# brazilian-ecommerce
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
Start with:

Business Problem and Problem Statement ==> Understand and write them
Objectives and Constraints ==> related with project
To predict Customer Satisfaction score for a given order based on given features like price, item_description, delivery_time and status……many more
This given problem can be solved either by:
1. Multi-Class Classification Problem, where in we can predict score [1,2,3,4,5] but what to do with 3 maybe remove them but what if there count is more
2. Binary Classification Problem, where in we can predict 0 as -ve or 1 as +ve)
3. Regression Problem where in we can go for predicting scores
Easy steps:

EDA(Univariate,Bivariate and Multivariate Analysis)+ data cleaning: check duplicate & missing data
Recency, Frequency, Monetary Value Analysis
Current status:
revenue (YoY)
order volume
customer order numbers
- first_purchase_month
-what is the median order price for customers who have X number of orders
-box plot: average spend per order
top product categories
number of items per order
Customer satisfaction:
average review score over time
top 3 & bottom 3 items score
Recommendation:
concern with current status
increase purchase frequency
increase order value
increase customer satisfaction
Advanced steps:

Correlation
Data Preprocessing + Feature Engineering
use Random Model, Naive Bayes and Logistic Regression as a baseline model
use Auto-Encoder Deep Learning model to extract few features
Model Selection (Prediction):SVM, Decision Tree, Random-Forest, XG-Boost, Cat-BoosT, Stacking Model maybe Voting Classifier
Summary
Deployment: deployed Best model using Streamlit
Improvements to Existing Approach
Machine Learning is playing a vital role in e-commerce and helping in:

Customer lifetime value (CLV)
Sales prediction
Next order prediction
Product recommendation
Review prediction
Sentiment analysis
Sentiment Analysis with customer review:

Data Wrangling:
- Load Data
- Remove Missing Data
- Label Sentiment
Pre Processing:
- Clear Text
- Apply Stemming
- Remove Stop Word
Modeling:
- Logistic Regression
-NOTE:
1. the fit_transform() function gives the same result as the function fit() and the transform() function
2. fit_transform() function only acts on training data, transform() acts on test data, and predict() acts on test data.
3. fit() performs or completes the training step, transform() changes the data in the pipeline to pass it on to the next stage in the pipeline, and fit_transform() does both the fitting and the transforming in one possibly short step.
Evaluate:
- Metrics
- Curve ROC
Hyperparametes Optimization:
- Random Search
- Grid Search
References:

https://www.kaggle.com/code/mukeshmanral/predicting-customer-satisfaction
https://www.kaggle.com/code/marcosmota/sentiment-analysis-using-logistic-regression
https://www.analyticsvidhya.com/blog/2021/04/sklearn-objects-fit-vs-transform-vs-fit_transform-vs-predict-in-scikit-learn/
