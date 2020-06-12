## Udacity_project_1(Write a Data Science Blog Post)
Python,Data Science,Machine Learning
## Libraries

import pandas as pd
from pandas.plotting import scatter_matrix
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import pandas_profiling
import random
import pickle
from sklearn.model_selection import StratifiedKFold
from sklearn import model_selection
from sklearn.model_selection import train_test_split
from sklearn import ensemble
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
from sklearn.naive_bayes import GaussianNB
from sklearn.linear_model import LogisticRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.ensemble import RandomForestRegressor
from sklearn.pipeline import Pipeline
from sklearn.model_selection import cross_val_score
from sklearn.svm import SVC
from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
from statsmodels.graphics.gofplots import qqplot
%matplotlib inline
from matplotlib import pyplot

## Business Problem

There is an ever-increasing focus on effective recruitment. An organization invests a lot of its time and resources in search of the potential candidates. The investment become loses if the selected candidates do not join the organization in the end.


## Objective
The objective of the analysis is to predict whether the dependent variable is to classify whether the potential customer will join with the organization or not? 

## Overview
Pose at least three questions related to business or real-world applications of how the data could be used.

1. The recruiters need to identify the chances of the potential candidates of joining the organization even before shortlisting their resumes for the interview process.

2. Numerous factors that can make a candidate back out from the job he/she is being selected for.

3. Difficulty to obtain a candidate's profile and employment records as the information is confidential and not easily available.


## Summary
I attached the summary image
 

## Acknowledgements
Attached the data set
Thank you to the Udacity team for creating this project and associated lessons.

## Conclusions
The prediction accuracy is 100%.
Precision and Recall are also 100%.
By the results, the predictions appear to be more biased. So we shall consider Logistic regression as better option for out problem.

