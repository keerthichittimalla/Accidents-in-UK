# Datascience-Practicum 1
## UK Accidents Monitoring System
## Overview
Road accidents is one of the main issues in the world from past many years. There are many accidents happening all over the world and are leading to the death of the person or injury. In 2020 approximately there were 1516 persons lost their lives in road accidents in UK. By using Open Road Safety Data for the 2020 dataset which is available in the government website, here i am performing data analysis, visualizations, machine learning algorithms and evaluating which model gives the best accuracy and confusion matrix in predicting the severity of accidents which will help the departments to identify the reason for accidents and take the necessary actions required to provide safety to the people.

## Data Source
Data was collected from the government website of UK. Here is the link for the data
•	https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-  safety-data 
 Used three csv files which was published on 16 October 2021
•	Road Safety Data - Casualties 2020
•	Road Safety Data - Vehicles 2020
•	Road Safety Data – Accidents 2020

## Steps Performed for Analysis:
•	Data Collection from Source
•	Data Preprocessing
•	Data Visualization
•	Data Modeling

## Data Modeling:
I have worked on few Supervised machine learning algorithms to check the accident severity and to predict which model gave the better results. Here i have split the data into train and test sets.
•	Gaussian Naïve Bayes
•	KNN
•	Decision Tree
•	Random Forest Classifier

<img width="642" alt="Screen Shot 2022-09-22 at 2 33 06 PM" src="https://user-images.githubusercontent.com/70365343/196062866-94636b54-564a-48b7-809e-5da802dfd1c2.png">

<img width="542" alt="Screen Shot 2022-09-22 at 2 33 30 PM" src="https://user-images.githubusercontent.com/70365343/196062905-b275f0d4-03a7-41ff-9395-907a5ed828ce.png">

<img width="548" alt="Screen Shot 2022-09-22 at 2 33 49 PM" src="https://user-images.githubusercontent.com/70365343/196062922-e4ed8620-0c1f-43a0-8be2-66b934ed8917.png">

<img width="662" alt="Screen Shot 2022-09-22 at 2 34 10 PM" src="https://user-images.githubusercontent.com/70365343/196062925-4ce0d83b-9d0e-413f-9485-be6f12683a0c.png">

## Analysis: 
After performing all the above steps i see that Random Forest classifier has given the good results compared to other models in predicting the severity of accidents. This analysis can be helpful for either police department or government of UK to take the necessary actions and reduce the number of accidents.

## Roadblocks: 
When i was merging the data and doing some clean up i see some issues in my code, and stack overflow has helped to overcome this error.
While performing machine learning algorithms i see some errors but the machine learning course which i have already completed helped me to overcome this error and there are also other references provided below which helped me to work on my project.

## References: 
Sarang Narkhede. (May 9, 2018). Understanding Confusion Matrix
https://towardsdatascience.com/understanding-confusion-matrix-a9ad42dcfd62

Himanshu Singh. (Jun 7, 2018). Supervised Learning Methods using Python
https://medium.com/@himanshuit3036/supervised-learning-methods-using-python-bb85b8c4e0b7 

Difference between Random Forests and Decision tree
https://stats.stackexchange.com/questions/285834/difference-between-random-forests-and-decision-tree 

Onel Harrison. (Sep 10, 2018). Machine Learning Basics with the K-Nearest Neighbors Algorithm
https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761 
