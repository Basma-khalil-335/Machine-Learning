# Medical Insurance Cost Prediction

## 1-Overview :
-This project represents a machine learning-based health insurance prediction system. Recently, many attempts have been made to solve this problem, as after Covid-19 pandemic, health insurance has become one of the most prominent areas of research. We have used the USA's medical cost personal dataset from kaggle, having 1338 entries. Features in the dataset that are used for the prediction of insurance cost include: Age, Gender, BMI, Smoking Habit, number of children etc. We used linear regression and also determined the relation between price and these features. We trained the system using a 80-20 split .

## 2-Gools :
- In this project We have used the USA's medical cost personal dataset from kaggle, having 1338 entries. Features in the dataset that are used for the prediction of insurance cost include: Age, Gender, BMI, Smoking Habit, number of children etc. We used linear regression and also determined the relation between price and these features. We trained the system using a 80-20 split .

## 3-Tools :
-
1- Numpy is is a python library for scientific computing.
-
-
2- Pandas is a Python library used for working with data sets.
-
-
3- sklearn is a simple and efficient tools for predictive data analysis.
-
## 4-Steps:

### -Dataset
- The dataset used is the sonar Rock vs Mine prediction from Kaggle.

### -Data Exploring
Dataset consists of 1338 records. Each record contains the below data for specific person.

age – Age of the person.
sex – Sex of the person.
bmi – Body Mass Index(BMI) of the person.
children – Number of children for the person.
smoker – Smoking status of the person.
region – Region of the person in US.
charges – Medical Insurance costs per year for the person.

### -EDA

![sex](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/c809388a-225e-4379-8f72-74541009f949)
![smoker](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/6fef1e7a-ca12-42ab-ab09-f63ac7b3be65)
![AGE](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/0b5a3d72-e5e5-445c-9328-6c11e39a3cbc)
![BMI](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/4720eaaa-2d1a-43dc-8602-82d4b46c0ac1)
![childern](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/b3693200-56ce-4c07-bd1c-aba847f5f7c1)
![region](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/40fa0ce0-d81a-48b6-a1df-3f242560f6e4)
![charge](https://github.com/Basma-khalil-335/Machine-Learning/assets/113937027/77238c20-f23a-4c38-8bf9-3f8b3cd10b06)

### -Data processing 
1- Check missing value - there are none
2- Categorical Feature
3- Categorical Feature transformation:
- Encoding 'sex , region , smoker'
4- Modeling
  - Splitting the features and Targete.
  - Splitting train & test data.
  - Modeling using Linear Regression.

 ### -Model Evaluation
 1- R squared value for the training_data_prediction is  0.7472945022920751 .
 2- R squared value for the test_data_prediction is  0.761829435021468 .



