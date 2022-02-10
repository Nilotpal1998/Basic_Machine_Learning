# **Advanced Regression Techniques used in Econometrics**
#### Implementations in a Real-World Dataset 
## Contents
This mainly contains some of advanced regression techniques that are taught in our econometrics course and I have tried to implement some of these into my present work on a simple real world data. These will mainly take care of the following topics:


1. Data Cleaning Details
2. Some simple EDA
3. **Multicollinearity** : Detection and Removal
4. Categorical Variables Treatment
5. **Heteroskedasticity** : Detection and Removal
6. **Endogeneity** : Detection and Removal


## Data Cleaning

![Data Cleaning Techniques](https://github.com/Nilotpal1998/Basic_Machine_Learning/blob/main/Econometrics/AdvRegTech.png "Advanced Regression Techniques")

## Exploratory data Analysis
These may contain necessary plots and inferences from the provided data . As in my case I have extensively used barplots , correlation plots , histograms , scatterplots , box plots , pie charts , doughnut plots , density plots and many more which are easily available in python seaborn and matplotlib packages.

![EDA](https://github.com/Nilotpal1998/Basic_Machine_Learning/blob/main/Econometrics/Hist.png "Histogram")

![EDA](https://github.com/Nilotpal1998/Basic_Machine_Learning/blob/main/Econometrics/Pie_Charts.png "Pie Charts")

## MultiCollinearity
**Definition**:Multicollinearity (or collinearity) occurs when one
independent variable in a regression model is linearly
correlated with another independent variable.

![EDA](https://github.com/Nilotpal1998/Basic_Machine_Learning/blob/main/Econometrics/CorrelationMatrix.png "Correlation Matrix")

**Detection**:
Variance Inflation factor

**Solution**:
Principal Component Analysis

## Categorical Variable Treatment
Categorical variables can be treated in three possible ways :

1. Dummy variable 
2. One Hot Encoding
3. Numerical Encoding

## Heteroskedasticity
**Definition**:
In simple terms, heteroscedasticity technically, refers to data with unequal variability (scatter) across a set of second, predictor variables.

**Detection**:
1. Breusche-Pagan Test
2. White test

**Solution**:
Log-transformation of the dependent variables.

![EDA](https://github.com/Nilotpal1998/Basic_Machine_Learning/blob/main/Econometrics/Heteroskedasticity.png "Scatter Plot giving evidence of Heteroskedasticity.")

## Endogeneity
**Definition**: In econometrics endogeneity refers to the situation where the explanatory variables become correlated with the error term.

**Detection**:
Hausman-Wu Test

**Solution**:
IV Regression Technique
