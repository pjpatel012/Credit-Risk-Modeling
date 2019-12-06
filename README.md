# Credit Risk Modeling
Evaluate risk with credit loans based on borrower financial history and loan terms. Publicly available data set by Prosper Loan. 

## Assignment Background

This project focus' primarily on machine learning tenchinques in python (Jupyternotebooks). 3 primary files are included in this project:
* Report ('Credit Risk Modeling.pdf')  
* Jupyternotebooks file - Models & Analysis ('Loan Risk.ipynb').  
* csv of the prosper loan data ('prosperLoanData1.csv')
* Variable Definition File ('Prosper Loan Data - Variable Definitions.xlsx')

## Prerequisites 

Jupyternotebooks is required to run the .ipynb file.

## Packages

For modeling, plotting, and statistical operations, the following libraries and modules are imported:

* import pandas as pd
* import numpy as np
* from time import time
* import matplotlib.pyplot as plt
* %matplotlib inline
* import seaborn as sb
* import warnings
* from sklearn.model_selection import train_test_split
* from sklearn.preprocessing import StandardScaler
* from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
* from sklearn import model_selection
* from sklearn.metrics import confusion_matrix
* from sklearn.metrics import accuracy_score
* from sklearn import svm
* from sklearn.ensemble import RandomForestClassifier
* from sklearn.linear_model import LinearRegression
* from sklearn.metrics import mean_squared_error

## Additional Data

Please note that the data used in this project is comprised of 8 years of data from Prosper Loan. This dataframe consists of over 113,000 rows and 81 columns. Since the prosperLoanData.csv is 100+ mb, a link is provided below to download the original dataset. A modified version of the dataset is provided in the repository for analysis. Please make sure all files are located in the same working directory before running.

https://docs.google.com/document/d/1qEcwltBMlRYZT-l699-71TzInWfk4W9q5rTCSvDVMpc/pub

## Authors

* **Paras Patel**
