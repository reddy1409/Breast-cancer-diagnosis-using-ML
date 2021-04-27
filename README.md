# Breast-cancer-diagnosis-using-ML
INTRODUCTION:
When the body’s cells start dividing without stopping and spread into the surrounding tissues it results in cancer. Cancer can start anywhere in the human body and one such cancer is breast cancer. Breast cancer is very common among women all over the world. For the year 2019 there have been 2.09 million cases all over the world with around 627000 deaths. Early diagnosis of the disease and giving the necessary treatment can result in early recovery. There has also been an increase in the number of cases each year and this is a matter of concern. In order to monitor for signs of the disease, screening once a year is highly recommended. The tumors can be either benign or malignant. Benign are the tumors which are not harmful and do not spread to the surrounding tissues while malignant are the cancerous tumors.
RELATED WORKS:
Siham A. Mohammed worked on a paper Analysis of Breast Cancer Detection Using Different Machine Learning Techniques where they focused on how to deal with imbalanced data that have missing values using resampling techniques to enhance the classification accuracy of detecting breast cancer. Three classifiers algorithms J48, NB, and SMO applied on two different breast cancer datasets were used.

Habib Dhahri, also worked on the same topic and proved that the three most popular evolutionary algorithms support vector machine, K-nearest neighbor, decision tree can achieve the same performance after effective configuration

OBJECTIVES OF STUDY:
By determining each factor in a cancer cell, we are going to check if the cancer cell in benign or malignant.
Using different algorithms like SVM and KNN we can predict the type of tumor and also see which algorithm gives more accuracy.

ABOUT THE DATASET:
I have collected the data from Kaggle. Wisconsin Diagnostic Breast Cancer (WDBC) dataset obtained by the university of Wisconsin Hospital is used to classify tumors as benign or malignant. The dataset we have used consists of 699 rows with different columns containing information about the lumps or tumors and the last column contains information if the tumor is benign or malignant.
EXPLORATORY DATA ANALYSIS:
The Dataset had 699 rows and 33 columns. There was an extra column in the table, which was removed, and the null values were extracted using isnull function. The sum of the null values was also shown. 
Visualizations:
 ![image](https://user-images.githubusercontent.com/63264474/116178706-b5053c80-a6db-11eb-80c6-faf7ce288d68.png)

The above visualization is a histogram with diagnosis on the X-axis and count on the Y-axis. The main aspect in finding the cancer to be serious or not by knowing if it is benign or malign. In the Data we have different features which help us to know if the cancer is benign or malign. From the above histogram we can see the blue one to be malign and the orange to be benign.
![image](https://user-images.githubusercontent.com/63264474/116178899-f1389d00-a6db-11eb-8c13-0d0185a35385.png)
 
The above pie chart represents the distribution of patients. The different colors represent benign and malign cases in the patients. These cases are determined after looking into all the cancer features in the patients.
![image](https://user-images.githubusercontent.com/63264474/116178919-fa296e80-a6db-11eb-9b9b-931b12f857ea.png)

A boxplot is drawn between features and diagnosis. Different features are taken of the X-axis and the Y-axis represents different values. Only few features are taken to get a precise boxplot. 
The Dark green color represents malign and light green represents benign. We can see difference in the values of the features.
![image](https://user-images.githubusercontent.com/63264474/116178943-044b6d00-a6dc-11eb-9a0b-bf0e0892c9c9.png)
A Heat map is drawn taking all the features into consideration. A heat map is used to check the correlation, and, in this case, we are using it to check the correlation between the different features. The lighter the color the stronger the correlation between the features. From the above heat map, we can see where we have the strongest correlation.

Data Analysis and Results:
From the above heatmap we can see some features play a major role for the prediction of the tumor. The next step is creating a model. The first step of creating the model is training and testing of the data. Here the first step is to split the entire data into training and testing where the test size can be passed as a parameter. 30 percent is given to test and 70 percent to train.
Standard scaling:
Here we are performing standardization by using the standard scalar function where all the values of features are converted into same unit. This is done for getting a better accuracy.
KNN and confusion matrix:
KNN is used to get a better accuracy of k value. For different values of k starting from 1-20 we are going to check the corresponding accuracy. 
An empty list is given to k. KNN algorithm needs n neighbors’ argument to be passed. 
For each k value the for loop is going to run. As the range is 20 the loop is going to run 20 times. For each k value we should fit the training set values and we are going to predict the testing values.
The confusion matrix and accuracy score are also imported to check how many values are predicted correctly.
The accuracy score gives us the accuracy of the model at the k value.
As we cannot go through all the values, a graph is plotted.
![image](https://user-images.githubusercontent.com/63264474/116178968-10372f00-a6dc-11eb-92ed-54aa4c6df80b.png)
SVM:
The SVM algorithm is also used to get the accuracy. After finding the accuracy using SVM we can conclude that the SVM gives a better accuracy when compared to KNN.

Conclusion:
Breast cancer is considered to be one of the significant causes of death in women. Early detection of breast cancer plays an essential role to save women’s life. Here using Python helps in providing the visualizations of different attributes. We can also see that SVM performs better than KNN and will have more accuracy.

Bibliography:
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data
https://towardsdatascience.com/building-a-simple-machine-learning-model-on-breast-cancer-data-eca4b3b99fa3
Mohammed S.A., Darrab S., Noaman S.A., Saake G. (2020) Analysis of Breast Cancer Detection Using Different Machine Learning Techniques. In: Tan Y., Shi Y., Tuba M. (eds) Data Mining and Big Data. DMBD 2020. Communications in Computer and Information Science, vol 1234. Springer, Singapore. https://doi.org/10.1007/978-981-15-7205-0_10












