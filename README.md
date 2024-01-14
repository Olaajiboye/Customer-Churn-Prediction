# ConnectTel Customer Churn Prediction <br>
## Introduction<br>
ConnectTel is a leading telecommunications company at the fore front of innovation and connectivity solutions.
With a strong presence in the global market, ConnectTel has established itself as a
trusted provider of reliable voice, data, and Internet services. Offering a comprehensive range of telecommunications solutions, including mobile networks, broad band connections, and enterprise solutions, ConnectTel caters to both individual and corporate customers, they are committed to providing exceptional customer service and cutting-edge technology.<br>
## Problem Overview
ConnectTel, a Telecom Company, is confronted with the urgent need to address customer churn, a significant threat to its business sustainability and growth. The company's current customer retention strategies lack precision and effectiveness, resulting in the loss of valuable customers to competitors.

To overcome this challenge, ConnectTel has set its sights on developing a robust customer churn prediction system. In this pursuit, they have reached out to you as a Data Scientist. 
## Objective
The goal is to leverage advanced analytics and machine learning techniques on available customer data, aiming to accurately forecast customer churn and implement targeted retention initiatives.
This proactive approach is expected to empower ConnectTel to reduce customer attrition, enhance customer loyalty, and maintain a competitive edge in the highly dynamic and competitive telecommunications industry.
## Project Analysis

1. Perform exploratory data analysis in Python
a)  Visualize relationships between the label and some key features
b)  Explore correlations
c)  Conduct univariate, bivariate, and multivariate analysis as much as is feasible

2. Perform feature engineering
a) Encoding categorical variables
b) Create new features from existing features where necessary, depending on insights from your EDA

3. Model selection, training, and validation
a) Train and test at least 3 supervised learning model

5. Model evaluation
a) Analyze the results of your trained model
b) What metrics are most important for the problem? Should the business be more concerned with better results on false negatives or true positives?<br>

## Methodology
The data was analyse using python. I also imported the neccessary library for the Project. The Library used are Pandas for Data prepprocessing, matplotlib.pyplot for Data Visualization, seaborn for Data Visualization, Counter for counting. <br>
This project is divided into three sections which are: <br>Data Import and Cleaning, <br>Data Analysis and Visualization, <br>Conclusion and Recommendation.

## Step 1: Importing the necessary libraries and load the Dataset.<br>
To get started, we need to import some useful libraries that will help us import the dataset into our python environment and also load the dataset.<br>
![Screenshot 2024-01-14 at 1 30 23 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/42de4b28-6d45-4287-b960-8773fdb7e324)

## Step 2: Understand the Dataset and Data cleaning
Each row in the dataset represents a different customer, and each column contains a different set of attributes.>br>
![Screenshot 2024-01-14 at 2 09 00 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/a28d5401-eeac-4d0b-ab17-fe5c438a9a6c) <br>
![Screenshot 2024-01-14 at 2 09 44 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/575c4e6d-b321-4647-a753-c743065f41f8) <br>
![Screenshot 2024-01-14 at 2 10 37 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/eb93c994-9768-47b8-8642-00930d4d1945)
## Step 3: Perform exploratory data analysis
### Distribution of Churn in the customer dataset.
![Screenshot 2024-01-14 at 2 18 03 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/4d73dd70-3a44-4d8c-bd60-41e7229ce1c6)<br>
The analysis above shows the number of customer who left the company. The visualization shows the number of people who left ConnectTel people.
### Visualize Distribution of Churn base on Gender
![Screenshot 2024-01-14 at 2 25 05 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/be14c41a-c05c-41df-83e2-a329bc7c081d)
The data analysis shows the distribution of Churn bas on Gender. The analysis reveal 
### Visualize Distribution of Churn base on Internet Service.
![Screenshot 2024-01-14 at 2 31 28 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/7d41b0bc-4663-4e33-a1d9-03ce00ed9b80)
![Screenshot 2024-01-14 at 2 31 38 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/8f482de9-1881-4190-b8fd-5450133acaf7)<br>
The analysis shows we have more customer churn who are Fiber optic user than other internet service. And we have less people leaving the company who are not internet users.<br>
From above graph, we see that customer with InternetService ‘Fiber optic’ has high chance to leave the company. Customers with ‘DSL’ internet service have the highest rate of staying and a lower rate of leaving. This gives us the impression that ‘DSL’ performs better than ‘Fibre Optics’.
### Visualize Distribution of Churn base on Contract.
![Screenshot 2024-01-14 at 2 41 48 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/a5b40b09-9f32-4d81-9dd3-2f2fb6bb3f71)
![Screenshot 2024-01-14 at 2 42 08 PM](https://github.com/Olaajiboye/Customer-Churn-Prediction/assets/152933091/b405b350-8b69-49e0-a268-1385c86d416b)<br>

The analysis shows we have more customer churn who are into Month to Month contract with the company that customers who are yearly or two years contract.
### Conclusion and Recommendation.
Exploratory data analysis is the process of analysing the main characteristics of a data set, typically using visualisation techniques and summary statistics. The goal is to comprehend the data, identify patterns and anomalies, and validate assumptions before proceeding with further analysis. <br>
From the above data analysis, we can conclude that there are some factors behind customer churn with the help of visualization. <br>
Throughout the analysis, I have learned several important things:
1) Factors such as Contract, Internet Service, Phone Service, Tenure appear to play a role in customer churn.
2) There does not seem to be a relationship between gender and churn.
3) Customers which have given a low satisfaction score in feedback are most likely to churn, so we must reach out to them to resolve any issues present.

