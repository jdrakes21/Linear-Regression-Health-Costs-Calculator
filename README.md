# Linear-Regression-Health-Costs-Calculator

The project involves building a linear regression model to predict healthcare costs based on a given dataset. The dataset contains information about various individuals, including attributes that might influence their healthcare expenses. The primary objective is to create a predictive model capable of estimating healthcare costs accurately based on the provided data.

Project Description:

1.This project focuses on the application of linear regression, a supervised machine learning algorithm, to predict healthcare costs.

2.The dataset includes various features like age, gender, BMI (Body Mass Index), number of children, smoking status, and healthcare expenses.

3.The initial steps involve data preprocessing, which includes converting categorical data to numerical values.

4.The dataset is then divided into two subsets: a training dataset (80% of the data) and a testing dataset (20% of the data).

5.The "expenses" column is separated from both datasets to create "train_labels" and "test_labels," which represent the target variable (healthcare expenses) for training and testing the model.

6.A linear regression model is created using the training dataset to learn the relationship between the input features and healthcare expenses.

7.The model is trained on the training dataset to optimize its parameters.

8.Finally, the model's performance is evaluated using the testing dataset, with the aim of achieving a Mean Absolute Error (MAE) of under 3500. This MAE represents the accuracy of the model's predictions, and it must be within $3500 to pass the challenge.

Objectives:

Data preprocessing: Convert categorical data to numerical values for model compatibility.

Dataset splitting: Divide the dataset into training and testing subsets.

Model creation: Build a linear regression model to predict healthcare costs.

Model training: Train the model using the training dataset to optimize its parameters.

Model evaluation: Evaluate the model's performance using the testing dataset and ensure that the MAE is under 3500.

Expected Outcome:

The expected outcome of the project is a well-trained linear regression model that can accurately predict healthcare costs based on the provided dataset. The model's performance, as measured by the MAE, should meet the requirement of being under 3500. The final cell of the notebook will predict healthcare expenses using the test dataset and graphically display the results, providing a visual representation of the model's accuracy. Successful completion of this challenge demonstrates the ability to preprocess data, build a predictive model, and evaluate its performance using linear regression, a fundamental technique in machine learning for regression tasks.
