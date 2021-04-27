# Breast-cancer-diagnosis-using-ML
INTRODUCTION:
When the body’s cells start dividing without stopping and spread into the surrounding tissues it results in cancer. Cancer can start anywhere in the human body and one such cancer is breast cancer. Breast cancer is very common among women all over the world. For the year 2019 there have been 2.09 million cases all over the world with around 627000 deaths. Early diagnosis of the disease and giving the necessary treatment can result in early recovery. There has also been an increase in the number of cases each year and this is a matter of concern. In order to monitor for signs of the disease, screening once a year is highly recommended. The tumors can be either benign or malignant. Benign are the tumors which are not harmful and do not spread to the surrounding tissues while malignant are the cancerous tumors.
List two or three related work such as publications and systems:
Siham A. Mohammed worked on a paper Analysis of Breast Cancer Detection Using Different Machine Learning Techniques where they focused on how to deal with imbalanced data that have missing values using resampling techniques to enhance the classification accuracy of detecting breast cancer. Three classifiers algorithms J48, NB, and SMO applied on two different breast cancer datasets were used.

Habib Dhahri, also worked on the same topic and proved that the three most popular evolutionary algorithms support vector machine, K-nearest neighbor, decision tree can achieve the same performance after effective configuration

Objectives of the study:
By determining each factor in a cancer cell, we are going to check if the cancer cell in benign or malignant.
Using different algorithms like SVM and KNN we can predict the type of tumor and also see which algorithm gives more accuracy.

About the dataset used:
I have collected the data from Kaggle. Wisconsin Diagnostic Breast Cancer (WDBC) dataset obtained by the university of Wisconsin Hospital is used to classify tumors as benign or malignant. The dataset we have used consists of 699 rows with different columns containing information about the lumps or tumors and the last column contains information if the tumor is benign or malignant.
Exploratory Analysis:
The Dataset had 699 rows and 33 columns. There was an extra column in the table, which was removed, and the null values were extracted using isnull function. The sum of the null values was also shown. 
Visualizations:
 ![image](https://user-images.githubusercontent.com/63264474/116178706-b5053c80-a6db-11eb-80c6-faf7ce288d68.png)

The above visualization is a histogram with diagnosis on the X-axis and count on the Y-axis. The main aspect in finding the cancer to be serious or not by knowing if it is benign or malign. In the Data we have different features which help us to know if the cancer is benign or malign. From the above histogram we can see the blue one to be malign and the orange to be benign.

 
The above pie chart represents the distribution of patients. The different colors represent benign and malign cases in the patients. These cases are determined after looking into all the cancer features in the patients.





