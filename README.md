# Sparkify-Customer-Churn-Prediction

### Content
1) Project Overview
2) Project Definition / Problem Statement
3) Software and Libraries
4) Files
5) Results 


## Project Overview
  Sparkify Customer Churn Prediction is a project done as a part of Capstone Project in the Udacity's Data Scientist Nanodegree. The project aimed at solving a business problem related to identfying customers that are likely to churn using their activity data. It requires me to understand customer behavior pattern from last 2 months of data.
  
## Project Definition / Problem Statement
Sparkify: It is a fictitious music app that has provided 2 months of the user behavior log data. The end-goal of this project was is to study customer behavior and predict the user churn and try to retain the user. The technologies used in this project include Python, SQL, PySpark, Machine Learning, Spark SQL, and many more. The main aspect was to predict the churn of users and prevent/regain the lost customers to get them back. The project also included data analysis and visualization, feature engineering, and model tuning
  
## Software and Libraries
  For this project, I have used Python, Jupyter notebooks, Pandas, Numpy, Spark, PySpark, Seaborn, and Matplotlib. Many other machine learning libraries have also been used perform essential functions of the project.
  
  This project could have also been done using cloud services like AWS/IBM/GCP/Azure with full dataset and employing clusters.
  
  
## Files
- Sparkify.ipynb : Jupyter notebook consisting all the codes and work for project
- README.me : readme file as in this file
- json file consisting data
- Blog [Link] (https://patel-parth4496.medium.com/sparkify-customer-churn-prediction-559b214c64ed)

## Results
  The outcome for this project can be stated as a machine learning model which is strongest in predicting if a customer churn's or not. 
  We have 2 models giving us the best f-1 scores, the lr, and the lrs. The lr model gave an f-1 score of 0.85 but if we closely see other outputs we can see overfitting and hence we should select the lrs model which gives us an f-1 score of 0.736. This score may look low/small but in a professional environment, any score above 0.7 is considered a good one.
  
  
## References
[1] https://mapr.com/blog/churn-prediction-pyspark-using-mllib-and-ml-packages/
Churn Prediction with PySpark using MLlib and ML Packages
[2] https://www.kaggle.com/blastchar/telco-customer-churn
Telco Customer Churn
[3] https://www.kaggle.com/c/kkbox-churn-prediction-challenge
WSDM — KKBox’s Churn Prediction Challenge
