# **Customer Churn Prediction**

## **Problem Definition**

The Customer Churn Prediction project focuses on predicting customer churn for a telecommunications company based in California during the second quarter of 2022. The dataset contains detailed information about 7,043 customers, including demographics, location, tenure, subscription services, and their status for the quarter (joined, stayed, or churned). Additionally, the project utilizes data from the Zip Code Population table to estimate populations for California zip codes.

The primary objective is to develop a predictive model that can determine whether a customer will churn, stay, or join the company based on the dataset's parameters.

### **Overview**

Machine Learning Models Applied and Accuracy
In our pursuit of predicting customer churn, we've employed several machine learning models, each with its unique strengths and characteristics. Let's delve into each of these models and explore their performance:

**Random Forest**
***Accuracy: 78.11%***

The Random Forest model is an ensemble learning method that combines multiple decision trees to make predictions. It excels in handling complex relationships within the data and is robust against overfitting. We applied this model to our dataset and achieved an accuracy rate of 78.11%.

**Logistic Regression**
***Accuracy: 78.28%***

Logistic Regression is a widely used classification algorithm for binary outcomes. It's simple yet effective in capturing linear relationships between features and the target variable. In our project, Logistic Regression yielded an accuracy rate of 78.28%.

**Naive Bayes Gaussian**
***Accuracy: 36.77%***

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem. We implemented the Gaussian variant, which is suitable for continuous data. However, it performed comparatively less well in our context, achieving an accuracy rate of 36.77%.

**Decision Tree**
***Accuracy: 77.29%***

Decision Trees are interpretable models that partition the data based on feature values to make predictions. While they tend to overfit, we fine-tuned the model to achieve an accuracy rate of 77.29%.

**XGB Classifier**
***Accuracy: 80.86%***

The XGBoost (Extreme Gradient Boosting) Classifier is a powerful ensemble learning algorithm known for its exceptional predictive performance. It excels in capturing complex relationships and minimizing errors. In our project, the XGB Classifier outperformed other models with an accuracy rate of 80.86%.



## **Data Exploration and Feature Engineering**

Our data exploration process included comprehensive analysis of customer demographics, subscription services, and geographic distribution. Feature engineering techniques were applied to extract valuable insights from the dataset, such as customer lifetime value and churn likelihood.

## **Application**

The ability to predict customer churn before it happens offers significant advantages to businesses. By identifying high-risk customers who are likely to churn, companies can take proactive actions to retain them. These actions may include:

Customer Success Initiatives: Reach out to high-risk customers to provide support and identify unmet needs.\
Service Quality Assessment: Calculate the churn rate to gauge how well the business is retaining customers, which reflects the quality and usefulness of its services.\

This project exemplifies the power of data science and machine learning in helping businesses make informed decisions to enhance customer retention and overall performance. Predicting customer churn is not only a means to reduce revenue loss but also a way to improve customer satisfaction and loyalty.

Please feel free to explore the code, models, and datasets in this repository. 
