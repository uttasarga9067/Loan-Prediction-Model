# Loan-Prediction-Model

#### This Notebook consists of 4 different Models trained for predicting if the Person is eligible for Loan, depending on the information provided in the Dataset

##### Printing the Dataset for checking various variables

###### 1].In the Dataset, we can see that Loan_Status is the Variable we want to predict, using all the variables present in the Dataset. This is where feature selection and feature engineering comes into picture. I have used some basic techniques to process the data in a way, so that we can use the same in our Model.
###### 2].Dealing with Outliers of the Dataset, while looking at the Number of Categorical and Numerical Features of the Dataset are some techniques that can be learned from this Notebook.
We can evaluate the Model on every step of our Progress


![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/1.PNG)

##### The Libraries that I have used for these Models are:
###### 1]. Numpy
###### 2]. Pandas
###### 3]. Matplotlib
###### 4]. Seaborn

##### The Notebook was developed using PySpark in Azure Databricks, a modern tool for end-to-end Machine Learning Development.

###### Below, the image belongs to the Schema of the Dataset.

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/2.PNG)

##### I have converted the Datatype for each of the Variables and performed Exploratory Data Analysis on the Dataset.

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/3.PNG)

### Exploratory Data Analysis
###### 1]. Distribution of loan granted based on the Gender:

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/4.PNG)

###### 2]. Distribution of loan granted based on the Marital Status:

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/5.PNG)

###### 3]. Distribution of loan granted based on the Employment Status:

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/6.PNG)


###### 4]. Distribution of loan granted based on the types of Properties and their Area:

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/7PNG)

###### 5]. Correlation Matrix of the Dataset:

![ScreenShot](https://github.com/uttasarga9067/Loan-Prediction-Model/blob/main/8PNG)

### Training and Testing 4 Models

###### 1]. Logistic Regression:       78% Accuracy
###### 2]. Support Vector Machines:   65% Accuracy
###### 3]. Decision Tree Classifier:  61% Accuracy
###### 4]. K-Nearest Neighbours:      61% Accuracy









