# Data Wrangling for Capstone Dataset

## Data Wrangling Steps

### Data Download

I downloaded the data from the **Machine Learning Repository** on **Heart Diseases**. You can visit this dataset [here](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). 

### Data Description

There are 4 datasets in this repository: *Long Beach health data, Hungary health data, Switzerland health data and Cleveland health data*. 

#### Number of Variables

In each of these datasets were **14** variables:

1.  (age) 
2.  (sex) 
3.  (cp) 
4.  (trestbps) 
5.  (chol) 
6.  (fbs) 
7.  (restecg) 
8.  (thalach) 
9.  (exang) 
10. (oldpeak) 
11. (slope) 
12. (ca) 
13. (thal) 
14. (num) (the predicted attribute) 

#### Number of Instances 

Number of Instances: 
          Cleveland: 303
          Hungarian: 294
        Switzerland: 123
      Long Beach VA: 200
      
#### Type of Data

Cross-sectional data from 1988. 

### Data Wrangling Steps 

#### Step 1
Downloaded the data in CSV format 
#### Step 2
Read the data into Jupyter Notebook
#### Step 3
Appended the data into a single dataset, *dataset* 
#### Step 4
Described the data and searched for anomalies and missing values 
##### Note: Missing values are given by '-9' in the dataset, however, there are also '?' entries 
#### Step 5 
Reframed the datafram to not take any '-9' or '?' values. This way, we do not delete any rows, and keep the missing values in the dataset. 
#### Step 6
Defined a new variable called **new_dhd** that took the value of **1** if dhd>=1, and **0** otherwise. 
#### Step 7
Data is saved and exported into a CSV file to be used for Data Storytelling. 
