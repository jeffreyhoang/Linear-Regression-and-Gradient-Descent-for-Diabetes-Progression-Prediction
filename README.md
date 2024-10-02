# Linear Regression and Gradient Descent for Diabetes Progression Prediction
 
# Diabetes Progression Prediction using Linear Regression

This project demonstrates the application of **linear regression** and optimization techniques such as **basic gradient descent** and **stochastic gradient descent (SGD)** to predict diabetes progression based on patient data. The project also utilizes the **Scikit-learn** library to build a linear regression model and compares the performance of custom-implemented models against Scikit-learn's model.

## Project Overview

The dataset consists of 442 diabetes patients, with 10 baseline variables including:
- Age
- Sex
- Body mass index (BMI)
- Average blood pressure
- Six blood serum measurements

The response variable is a quantitative measure of **disease progression** one year after baseline.

### Key Tasks
1. **Data Preparation**: Split the dataset into training, validation, and testing sets (60% training, 20% validation, 20% testing).
2. **Scikit-learn Linear Regression**:
   - Implemented the linear regression model using Scikit-learn's `LinearRegression()`.
   - Extracted the bias and weights from the model.
   - Calculated errors for training, validation, and testing datasets.
3. **Basic Gradient Descent**:
   - Implemented linear regression using basic gradient descent from scratch.
   - Tuned parameters to match Scikit-learn model accuracy.
   - Displayed learning curves for training and validation errors using **Matplotlib**.
4. **Stochastic Gradient Descent**:
   - Implemented linear regression using stochastic gradient descent.
   - Displayed learning curves showing error progression along batches.
   - Tuned parameters for accuracy similar to the Scikit-learn model.

## Results

### Scikit-learn Linear Regression
- **Bias**: [151.03]
- **Weights**: 
    - [0.85123913 -10.78705929  28.35338275  17.35952702 -31.57426388, 16.92370006   0.69631007   6.8214824   28.3586807    1.48736662]
- **Training Dataset Error**: 1473.43
- **Validation Dataset Error**: 1207.85
- **Testing Dataset Error**: 1622.81

### Basic Gradient Descent
- **Bias**: [151.02]
- **Weights**: 
    - [1.31, -10.70, 28.99, 17.17, -4.83, -4.60, -10.41, 4.58, 17.53, 1.64]
- **Training Dataset Error**: [1480.31]
- **Validation Dataset Error**: [1220.99]
- **Testing Dataset Error**: [1650.93]

### Stochastic Gradient Descent
- **Bias**: [150.50]
- **Weights**: 
    - [1.30, -10.40, 29.15, 17.33, -6.20, -3.22, -9.49, 5.16, 17.78, 1.51]
- **Training Dataset Error**: [1479.96]
- **Validation Dataset Error**: [1227.62]
- **Testing Dataset Error**: [1654.01]

## Learning Curves

### Basic Gradient Descent Learning Curve
<img width="865" alt="Screenshot 2024-09-28 at 12 11 58 AM" src="https://github.com/user-attachments/assets/0a4f0ffa-cdaf-4ddf-8969-be57c315f712">


### Stochastic Gradient Descent Learning Curve
![Screenshot 2024-10-01 at 9 10 55 PM](https://github.com/user-attachments/assets/a2cd8e2d-4f19-4e34-b22e-5d75c71b1b2f)




