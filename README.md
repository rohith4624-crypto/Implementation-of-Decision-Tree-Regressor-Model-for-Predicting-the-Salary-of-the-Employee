# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: ROHITH R
RegisterNumber:  25002211
*/
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeRegressor
print("Dataset:\n", dataset.head())
X = dataset[['Level']].values
y = dataset['Salary'].values
model = DecisionTreeRegressor(random_state=0)
model.fit(X, y)
y_pred = model.predict([[6]])
print("\nPredicted Salary for Level 6:", y_pred)
X_grid = np.arange(min(X), max(X), 0.01)
X_grid = X_grid.reshape((len(X_grid), 1))
plt.scatter(X, y)
plt.plot(X_grid, model.predict(X_grid))
plt.title('Decision Tree Regression')
plt.xlabel('Level')
plt.ylabel('Salary')
plt.show()

```

## Output:
<img width="362" height="160" alt="Screenshot 2026-03-09 105120" src="https://github.com/user-attachments/assets/93255235-308a-45fe-a198-1f2c65f7fd79" />
<img width="424" height="50" alt="Screenshot 2026-03-09 105147" src="https://github.com/user-attachments/assets/c74526e5-3b5b-4095-8f5f-329b2f728013" />
<img width="723" height="557" alt="Screenshot 2026-03-09 105131" src="https://github.com/user-attachments/assets/99c56d9a-f54d-4839-825f-e7901d388646" />

## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
