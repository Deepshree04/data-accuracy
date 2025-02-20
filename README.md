# Improving Data Accuracy in CRM using AI
This repository contains the code for the project titled "Improving Data Accuracy in CRM using AI". This project uses customer segmentation, customer churn analysis, sentiment analysis and businImproving Data Accuracy in CRM using AIess intelligence to transform CRM. 2 datasets have been used for this project. The first dataset [1] has been obtained from [Kaggle.](https://www.kaggle.com/datasets/jpacse/datasets-for-churn-telecom) This dataset contains a total of 20,000 entries and 58 columns and is used for customer segmentation and churn analysis. The second dataset [2] has been scraped from twitter using the twitter API, and the collected tweets are used as reviews for sentiment analysis. This dataset was labelled manually. [1] was segmented into 3 clusters using K-means clustering, and a highest accuracy of 73% using XGBoost was obtained for customer churn analysis. For sentiment analysis, a highest accuracy of 90% using Multinomial Naive Bayes and Stochastic Gradient Descent was obtained after pre-prcoessing of the tweets/reviews in [2].

The following machine learning algorithms were used for customer segmentation:
- K-means clustering

The following machine learning algorithms were used for customer churn analysis:
- XGBoost
- Decision Tree
- Stochastic Gradient Descent
- Logistic Regression

The following machine learning algorithms were used for sentiment analysis:
- Multinomial Naive Bayes
- Stochastic Gradient Descent
- Decision Tree
- Support Vector Machine
- Logistic Regression

PowerBI from Microsoft was used as the business intelligence tool.

