# Jamboree-Education---Linear-Regression
## Context

Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

## Dataset link :
https://www.kaggle.com/code/ranitsarkar01/jamboree-linear-regression/input?select=jamboree_dataset.csv

## Column Profiling:

|Features                                                    |Description          |
|------------------------------------------------------------|---------------------|
|Serial No.                                                  |Unique row ID        |
|GRE Scores                                                  |out of 340           |
|TOEFL Scores                                                |out of 120           |
|University Rating                                           |out of 5             |
|Statement of Purpose and Letter of Recommendation Strength  |out of 5             |
|Undergraduate GPA                                           |out of 10            |
|Research Experience                                         |either 0 or 1        |
|Chance of Admit                                             |ranging from 0 to 1  |

## Concept Used:

•	Exploratory Data Analysis

•	Linear Regression

## Study contains:

**1.	Exploratory Data Analysis:**

o	Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), missing value detection, statistical summary.

o	Univariate Analysis (distribution plots of all the continuous variable(s) bar plots/count plots of all the categorical variables)

o	Bivariate Analysis (Relationships between important variables and count)

o	Illustrate the insights based on EDA

**2.	Data Preprocessing:**

o	Duplicate value check

o	Missing value treatment

o	Outlier treatment

o	Feature engineering

o	Data preparation for modelling

**3.	Model building:**

o	Build the Linear Regression model and comment on the model statistics.

o	Try out Ridge and Lasso regression.

**4.	Testing the assumptions of the linear regression model**

1.	Multicollinearity check by VIF score (variables are dropped one-by-one till none has VIF>5)

2.	The mean of residuals is nearly zero.
	
3.	Linearity of variables (no pattern in the residual plot)
	
4.	Test for Homoscedasticity
	
5.	Normality of residuals (almost bell-shaped curve in residuals distribution, points in QQ plot are almost all on the line)
  
**5.	Model performance evaluation:**

o	Metrics checked- MAE, RMSE, R2, Adjusted R2

o	Train and test performances are checked.

**6.	Insights & Recommendations**
