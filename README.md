# Predicting Insurance Premiums
## Comparative Analysis of Machine Learning Algorithms   
*Demo link https://insurancepremium.onrender.com/*
#### The purpose of this project is to develop a predictive model for insurance premium estimation based on a dataset obtained from Kaggle. The dataset consists of various factors such as age, sex, body mass index (BMI), number of children, smoking status, region, and insurance expenses. The objective is to explore the dataset, preprocess the data, and evaluate the performance of different machine learning algorithms in predicting insurance expenses accurately.
## Data Exploratory Analysis
#### Initially, the dataset is examined to gain insights and understanding. The dataset comprises 1,338 instances with seven columns. Descriptive statistics are calculated to summarize the data. To prepare the categorical values for machine learning algorithms, label encoding is performed on the 'sex' and 'smoker' columns. One-hot encoding is then applied to transform these categorical variables into numerical features.
## Model Development and Evaluation
#### The dataset is divided into training and testing sets using a 80:20 split. Three machine learning algorithms are employed for insurance premium prediction: Linear Regression, Decision Tree, and Random Forest. The models are trained on the training set and evaluated on the testing set. Mean squared error (MSE) and coefficient of determination (R^2) are utilized as evaluation metrics to assess the performance of each algorithm.
## Results
#### The obtained results demonstrate the effectiveness of the implemented machine learning algorithms. The Linear Regression model achieved an R^2 score of 0.800, indicating a reasonable predictive performance. The Decision Tree model performed slightly better with an R^2 score of 0.843, suggesting a stronger ability to capture the complexities within the data. The Random Forest model exhibited the highest predictive accuracy, with an R^2 score of 0.896, highlighting its capability to produce more precise estimates for insurance premiums.
## Conclusion
#### In this project, a comprehensive analysis was conducted to predict insurance premiums based on the provided dataset. By employing Linear Regression, Decision Tree, and Random Forest algorithms, it was observed that the Random Forest model outperformed the other models in terms of predictive accuracy. This study provides insights into the potential of machine learning techniques for insurance premium estimation, enabling insurance companies to make more informed decisions. Future work could involve further feature engineering, exploring other algorithms, and incorporating additional datasets to enhance the accuracy and robustness of the predictive models for insurance premium prediction.
