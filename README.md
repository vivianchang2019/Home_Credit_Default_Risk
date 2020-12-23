# Kaggle Competition : Home Credit Default Risk

> Predict how capable each applicant is of repaying a loan.

> The best scores till now is **0.73387**, using XGBoost without PCA. 

References:<br>
[Data Sources](https://www.kaggle.com/c/home-credit-default-risk/data) <br>
[Start Here: A Gentle Introduction](https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction)
<br>
[Credit Fraud || Dealing with Imbalanced Datasets](https://www.kaggle.com/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets) <br>


## Notebook explanation: 
## 1. HCDR_01.ipynb: 
> Analyzing data by EDA, do Feature Engineering and fit data with ML models (Logistic Regression, Random Forest, XGBoost & Grid search)
## 2. HCDR_02.ipynb: 
> Use Under-sampling and Over-Sampling (SMOTE) to fix imbalanced data problem. 
## 3. HCDR_03.ipynb: 
> Use Dimension reduction (PCA) to improve speed on training (Use pipeline). 


--------------
<br><br>

## Detail Summary of each notebook.

### version 1 : Fit data with ML models (Logistic Regression, Random Forest, XGBoost & Grid search)

> Notebook : HCDR_01.ipynb

task:
1. Check dataset
2. EDA (Exploratory Data Analysis)
3. Data Processing
4. Fit different models and make prediction
5. Predict the data for kaggle submission

#### kaggle submission result 

![submission result](https://github.com/vivianchang2019/Home_Credit_Default_Risk/blob/master/result/HCDR.JPG?raw=true)


--------------------

### version 2 :  Use Under-sampling and Over-Sampling (SMOTE) to fix imbalanced data problem. 

> Notebook : HCDR_02.ipynb

task:
1. Check dataset
2. Data Processing
3. Under-sampling
4. Over-sampling (SMOTE Technique)

--------------------

### version 3 :  Use Dimension reduction (PCA) to improve speed on training. 

> Notebook :  HCDR_03.ipynb

task:
1. Check dataset
2. Data Processing
3. Dimension reduction (PCA)
4. Fit different models and make prediction
5. Predict the data for kaggle submission

![submission result](https://github.com/vivianchang2019/Home_Credit_Default_Risk/blob/master/result/HCDR_02.JPG?raw=true)