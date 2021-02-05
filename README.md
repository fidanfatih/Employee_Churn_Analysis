# Employee_Churn_Prediction


WELCOME!¶
Welcome to "Employee Churn Analysis Project". This is the second project of Capstone Project Series, which you will be able to build your own classification models for a variety of business settings.
Also you will learn what is Employee Churn?, How it is different from customer churn, Exploratory data analysis and visualization of employee churn dataset using matplotlib and seaborn, model building and evaluation using python scikit-learn package.
You will be able to implement classification techniques in Python. Using Scikit-Learn allowing you to successfully make predictions with the Random Forest, Gradient Boosting Descent, KNN algorithms.
At the end of the project, you will have the opportunity to deploy your model using Streamlit.
Before diving into the project, please take a look at the determines and project structure.
* NOTE: This tutorial assumes that you already know the basics of coding in Python and are familiar with model deployement as well as the theory behind K-Means, Gradient Boosting Descent, KNN, Random Forest, and Confusion Matrices.
#Determines
In this project you have HR data of a company. A study is requested from you to predict which employee will churn by using this data.
The HR dataset has 14,999 samples. In the given dataset, you have two types of employee one who stayed and another who left the company.
You can describe 10 attributes in detail as:
* satisfaction_level: It is employee satisfaction point, which ranges from 0-1.
* last_evaluation: It is evaluated performance by the employer, which also ranges from 0-1.
* number_projects: How many of projects assigned to an employee?
* average_monthly_hours: How many hours in averega an employee worked in a month?
* time_spent_company: time_spent_company means employee experience. The number of years spent by an employee in the company.
* work_accident: Whether an employee has had a work accident or not.
* promotion_last_5years: Whether an employee has had a promotion in the last 5 years or not.
* Departments: Employee's working department/division.
* Salary: Salary level of the employee such as low, medium and high.
* left: Whether the employee has left the company or not.
First of all, to observe the structure of the data, outliers, missing values and features that affect the target variable, you must use exploratory data analysis and data visualization techniques.
Then, you must perform data pre-processing operations such as Scaling and Label Encoding to increase the accuracy score of Gradient Descent Based or Distance-Based algorithms. you are asked to perform Cluster Analysis based on the information you obtain during exploratory data analysis and data visualization processes.
The purpose of clustering analysis is to cluster data with similar characteristics. You are asked to use the K-means algorithm to make cluster analysis. However, you must provide the K-means algorithm with information about the number of clusters it will make predictions. Also, the data you apply to the K-means algorithm must be scaled. In order to find the optimal number of clusters, you are asked to use the Elbow method. Briefly, try to predict the set to which individuals are related by using K-means and evaluate the estimation results.
Once the data is ready to be applied to the model, you must split the data into train and test. Then build a model to predict whether employees will churn or not. Train your models with your train set, test the success of your model with your test set.
Try to make your predictions by using the algorithms Gradient Boosting Classifier, K Neighbors Classifier, Random Forest Classifier. You can use the related modules of the scikit-learn library. You can use scikit-learn Confusion Metrics module for accuracy calculation. You can use the Yellowbrick module for model selection and visualization.
In the final step, you will deploy your model using Streamlit tool.
#Tasks
1. Exploratory Data Analysis
* Importing Modules
* Loading Dataset
* Data Insigts
2. Data Visualization
* Employees Left
* Determine Number of Projects
* Determine Time Spent in Company
* Subplots of Features
3. Data Pre-Processing
* Scaling
* Label Encoding
4. Cluster Analysis
* Find the optimal number of clusters (k) using the elbow method for for K-means.
* Determine the clusters by using K-Means then Evaluate predicted results.
5. Model Building
* Split Data as Train and Test set
* Built Gradient Boosting Classifier, Evaluate Model Performance and Predict Test Data
* Built K Neighbors Classifier and Evaluate Model Performance and Predict Test Data
* Built Random Forest Classifier and Evaluate Model Performance and Predict Test Data
6. Model Deployement
* Save and Export the Model as .pkl
* Save and Export Variables as .pkl

