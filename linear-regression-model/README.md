# Linear Regression Model

## Purpose

This code is designed to illustrate the application of linear regression using two distinct datasets: the Diabetes dataset  and the Boston Housing dataset.

Structure: 
-Dataset
-Data Split
-Linear Regression Model
-Prediction Results
-Scatter Plots


## Data Summary

### Diabetes Dataset:

The Diabetes dataset is a collection of data from 442 diabetes patients, encompassing ten baseline variables, including age, sex, body mass index, average blood pressure, and six blood serum measurements. The dataset serves as a valuable resource for machine learning tasks, particularly in regression analysis, with the goal of predicting a quantitative measure of disease progression one year after the baseline.

**Dataset Characteristics:**

-   **Number of Instances:** 442
-   **Number of Attributes:** The dataset comprises 10 numeric predictive values in its first 10 columns.
-   **Target Variable:** The response of interest is found in column 11, representing a quantitative measure of disease progression one year after the baseline.

**Attributes:**

1.  **age:** Age in years
2.  **sex:** Gender
3.  **bmi:** Body mass index
4.  **bp:** Average blood pressure
5.  **s1:** Total serum cholesterol (tc)
6.  **s2:** Low-density lipoproteins (ldl)
7.  **s3:** High-density lipoproteins (hdl)
8.  **s4:** Total cholesterol / HDL ratio (tch)
9.  **s5:** Possibly log of serum triglycerides level (ltg)
10.  **s6:** Blood sugar level (glu)



--------------------
  
  ### Boston Housing Dataset:
The Boston Housing dataset provides information on housing attributes in the Boston area. It is commonly used in regression tasks to predict the median value of owner-occupied homes (medv). The dataset was obtained from GitHub and includes various features related to housing characteristics. **Data Set Characteristics:** 
- **Number of Instances:** 506 
-  **Number of Attributes:** 14 (13 feature variables and  1 target variable)
- **Target Variable:** medv (median value of owner-occupied homes)

- **Attribute Information:**
-- 1. crim: Per capita crime rate by town 
--2. zn: Proportion of residential land zoned for lots over 25,000 sq. ft. 
--3. indus: Proportion of non-retail business acres per town 
--4. chas: Charles River dummy variable (1  if tract bounds river; 0 otherwise) 
--5. nox: Nitric oxides concentration (parts per 10 million) 
--6. rm: Average number of rooms per dwelling 
--7. age: Proportion of owner-occupied units built before 1940  
--8. dis: Weighted distances to five Boston employment centers 
--9. rad: Index of accessibility to radial highways 
--10. tax: Full-value property tax rate per $10,000  
--11. ptratio: Pupil-teacher ratio by town 
--12. b: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town 
--13. lstat: Percentage of lower status of the population