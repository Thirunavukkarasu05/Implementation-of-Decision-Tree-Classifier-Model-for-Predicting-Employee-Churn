# Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the required libraries.
2. Upload and read the dataset.
3. Check for any null values using the isnull() function.
4. From sklearn.tree import DecisionTreeClassifier and use criterion as entropy.
5. Find the accuracy of the model and predict the required values by importing the required module from sklearn.
6. End the Program.

## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by: Thirunavukkarasu P
RegisterNumber:  212222040173
*/
/*

import pandas as pd
data=pd.read_csv("Employee.csv")

data.head()

data.info()

data.isnull().sum()

data['left'].value_counts()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()

data["salary"]=le.fit_transform(data["salary"])
data.head()

x = data[["satisfaction_level","last_evaluation","number_project","average_montly_hours","time_spend_company","Work_accident","promotion_last_5years","salary"]]
x.head()

y = data["left"]

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test = train_test_split(x,y,test_size=0.2,random_state=100)

from sklearn.tree import DecisionTreeClassifier
dt = DecisionTreeClassifier(criterion = "entropy")
dt.fit(x_train,y_train)
y_pred = dt.predict(x_test)

from sklearn import metrics
accuracy = metrics.accuracy_score(y_test,y_pred)
print(accuracy)

dt.predict([[0.5,0.8,9,260,6,0,1,2]])
*/
```

## Output:
![1](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/f6288f57-92e5-4216-959d-49cbd1e1ab6b)
![2](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/34fc28e1-b521-4e40-8284-f08b2f628db0)
![3](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/4c4326a4-c2cb-43bf-ae80-673e947242ec)
![4](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/6f89ef79-d683-4924-ab8c-d5dfefc6831a)
![5](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/34e2e3cd-d43e-4753-afdd-6e0f28de01ee)
![6](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/28ebe6b3-c8e6-43f3-a608-664e57ccabd2)
![7](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/4061623f-24c1-42ec-9ab2-c7e9f96e6fdc)
![8](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/8de55d03-d33a-45a8-9222-6eef1b59fa3f)





## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
