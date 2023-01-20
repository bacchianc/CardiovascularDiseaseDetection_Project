# ML_Classification_Project

## 1.Introduction

  This project is focuses on building a Model to predict Cardiovascular Disease.

  The value of a health is more than anything. Here we used some features and values were collected at the moment of medical  examination.

#### Algorithm Used:
   Logistic Regression,KNN Model and GridSearchCV



#### Features:
  1.	Age | Objective Feature | age | int (days)
  2.	Height | Objective Feature | height | int (cm) |
  3.	Weight | Objective Feature | weight | float (kg) |
  4.	Gender | Objective Feature | gender | categorical code |
  5.	Systolic blood pressure | Examination Feature | ap_hi | int |
  6.	Diastolic blood pressure | Examination Feature | ap_lo | int |
  7.	Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
  8.	Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
  9.	Smoking | Subjective Feature | smoke | binary |
  10.	Alcohol intake | Subjective Feature | alco | binary |
  11.	Physical activity | Subjective Feature | active | binary |         
            
#### Target:
   Presence or absence of cardiovascular disease | Target Variable | cardio | binary |
   
   
   
   
   
 ## 2. Solution approach Using Logistic Regression

   2.1 Import Necessary Libraries

   2.2 Loading the Cardio Dataset

   2.3 Take a Quick Look at the Data Structure

   2.4.Selecting Features to a Model Build
   
2.5 Information About Data
   
2.6 Data Preprocessing (Analysis (EDA))
   
2.7 Visualize the Data Using graphs
   
2.8 Dealing with Outliers
   
2.9 Dividing the Dataset into Features and Label
   
2.10 Checking the relationship of Features with Label
   
2.12 Checking for the multicollinearity in Features

2.13 Data splitting for training the Model

2.14 Building a Model Using The Logistic Regression
   
2.15 Calculating the Accuracy of Model





## 3. Solution Approach using KNN


3.1 Importing Libraries

3.2 Building a Model

3.3  Accuracy Calculation and Confusion Matrix

3.4 Hypertune the model using GridSearchCV

3.5 Accuracy Calculation and Confusion Matrix after Tune the Model



## 4. Results

### 4.1 Using Logistic Regression:

##### Model Accuracy:  0.71



### 4.2 Using KNN Model:

##### Model Accuracy:  0.68



### 4.2 Using KNN Model after HyperTune:

##### Model Accuracy:  0.70




## 5. Conclusion

There are real world problems that can be solved with machine learning. Some of these solutions can take real world data and make very accurate predictions that can be useful to our daily lives. Users can leverage the power of machine learning without being data scientist when easy to use applications are built around some of these complicated models.
