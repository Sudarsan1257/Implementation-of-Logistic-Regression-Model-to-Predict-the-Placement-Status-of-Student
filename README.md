# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Collect the Dataset
Obtain the student dataset containing independent variables
(e.g., CGPA, aptitude score, technical skills, internships, etc.)
and the dependent variable Placement Status (Placed / Not Placed).

2.Define Variables
Let X be the independent variables (features).
Let Y be the dependent variable (Placement Status: 0 or 1).

3.Preprocess the Data
Handle missing values.
Encode categorical variables into numerical form.
Scale or normalize features if required.

4.Split the Dataset
Divide the dataset into training set and testing set.
Initialize Model Parameters
Initialize weights w and bias b to zero (or small random values).

5.Compute the Linear Combination
For each data point, compute:
z=wX+b

6.Apply the Sigmoid Function
Convert the linear output into probability using:​
<img width="249" height="87" alt="Screenshot 2026-02-06 105226" src="https://github.com/user-attachments/assets/90d0eda1-a7b9-4972-8363-2d97fa4402b7" />

7.Calculate the Loss Function
Compute the log loss (binary cross-entropy) to measure prediction error.

8.Update Parameters Using Gradient Descent
Adjust weights and bias iteratively using the learning rate α:
<img width="306" height="159" alt="image" src="https://github.com/user-attachments/assets/98ff61ce-1c5d-4341-927d-d14f945fbd02" />

9.Repeat Until Convergence
Repeat steps 6–9 for a fixed number of iterations or until the loss is minimized.

10.Make Predictions
Predict placement status using:
<img width="385" height="102" alt="image" src="https://github.com/user-attachments/assets/90df2203-980f-43ec-b15a-d36b86c927dd" />

11.Evaluate the Model
Measure performance using accuracy, confusion matrix, precision, recall, or F1-score.

## Program:
```
/*
Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.
Developed by: 
RegisterNumber:  
*/
```
```

```

## Output:
TOP 5 ELEMENTS
<img width="1320" height="263" alt="image" src="https://github.com/user-attachments/assets/501dd7e9-e215-4b6d-8b0b-0e8d77e4fced" />
<img width="1178" height="254" alt="image" src="https://github.com/user-attachments/assets/6ff79e02-3b3b-40eb-be06-ecc1797e5ec7" />

PRINT DATA
<img width="1109" height="554" alt="image" src="https://github.com/user-attachments/assets/5ee2d713-9e50-4ff1-827e-2ef8cffb51b5" />

CONFUSION ARRAY
<img width="781" height="74" alt="image" src="https://github.com/user-attachments/assets/937f713b-9794-4ce7-95e5-ef22165884d0" />

ACCURACY VALUE
<img width="326" height="59" alt="image" src="https://github.com/user-attachments/assets/0255961c-121f-44b3-82ab-1d00cda6c918" />

CLASSFICATION REPORT
<img width="286" height="67" alt="image" src="https://github.com/user-attachments/assets/b6e2251d-7921-4e20-aebd-719cf74ecc75" />
<img width="651" height="223" alt="image" src="https://github.com/user-attachments/assets/b86fc18e-adba-4510-868f-1b25059a156e" />

PREDICTION
<img width="555" height="55" alt="image" src="https://github.com/user-attachments/assets/489cb28d-75c2-4199-bc3f-e20a54fb7fa5" />


## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
