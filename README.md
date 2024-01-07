# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1

import pandas as pd
### Step2
read the file

### Step3
Get the value of X and Y variable

### Step4
Create the linear regression model and fit

### Step5
predict the Co2 emmission of a car where the weight is 2300kg,and the volume is 1300cm cube
## Program:
```

#Developed by Yuvaraj V
#Reg.no: 23013769
import pandas as pd
from sklearn import linear_model
df=pd.read_csv('/content/drive/MyDrive/cars (1).csv')
a=df[["Weight","Volume"]]
b=df[["CO2"]]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))




```
## Output:

### Insert your output


![293402674-b876fa46-9a5b-4426-8c24-d92a1a8ccf46](https://github.com/nainamohamed09642/Multivariate-Linear-Regression/assets/151916360/6707ee2a-7e18-4e9f-adad-a34f0da56bf1)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
