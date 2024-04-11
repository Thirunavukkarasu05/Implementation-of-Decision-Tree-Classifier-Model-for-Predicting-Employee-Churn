# Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import libraries and use LabelEncoder to transform categorical 'salary' data into numerical labels.
2. Choose relevant features ('satisfaction_level', 'last_evaluation', etc.) and target variable ('left') from the dataset.
3. Divide the dataset into training and testing sets using train_test_split with specified test size and random state.
4. Initialize a DecisionTreeClassifier with 'entropy' criterion and fit it to the training data.
5. Predict 'left' values for testing data, calculate accuracy using metrics.accuracy_score, and make predictions for new input features.


## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by: Thirunavukkarasu P
RegisterNumber:  212222040173
*/
/*
import pandas as pd
data=pd.read_csv("G:/jupyter_notebook_files/employee_churn/Employee.csv")
data.head()
data.info()
data.isnull().sum()
data['left'].value_counts()
from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data['salary']=le.fit_transform(data['salary'])
data.head()
x=data[['satisfaction_level','last_evaluation','number_project','average_montly_hours','time_spend_company','Work_accident','promotion_last_5years','salary']]
x.head()
y=data['left']
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=100)
from sklearn.tree import DecisionTreeClassifier
dt=DecisionTreeClassifier(criterion='entropy')
dt.fit(x_train,y_train)
y_predict=dt.predict(x_test)
from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_predict)
accuracy
dt.predict([[0.5,0.8,9,260,6,0,1,2]])
*/
```

## Output:
![1](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/692d50cd-b35f-4b05-a2f9-dfb64a62663a)
![2](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/b9cf0602-4765-4d41-a792-76f2c68f3c8d)
![3](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/c4b691c7-513b-485c-9ec1-2de06bf9a769)
![4](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/12a47919-5208-4b61-92da-3de141bd1e5a)
![5](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/63e65a06-df52-476e-9d85-6e37f7a2d724)
![6](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/f91c0fe9-3939-4808-bd76-16cf91034186)
![7](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/d86f349f-6a49-4d03-8874-d6340c5f69bc)
![8](https://github.com/Thirunavukkarasu05/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/119291645/5e128a7d-1d25-4389-8637-7d79ebbc7aa2)




## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
