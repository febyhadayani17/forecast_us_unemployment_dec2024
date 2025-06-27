# Forecasting US Unemployment Rate (U3) in Dec 2024 Using Linear Backward Regression

- Context:  By using linear regression with backward selection on lagged macroeconomic variables, we will predict U-3 Unemployment Rate for December 2024 to help policymakers make prediction and identify factors that affect the unemployment rate
- Approach:
Linear Regression with backward selection and lagged variables on macroeconomic indicators.
- Gaps Addressed by Our Model:
  - Employs backward elimination to refine predictors and improve regression model accuracy.
  - Incorporates lagged variables for key predictors to handle autocorrelation.
  - Create dummy variables for years to capture yearly effects.
  - Trained on more recent data

## 📁 Dataset
![image](https://github.com/user-attachments/assets/b4c1681b-d567-4ddd-8618-1ec2987b443b)

## 🔧 Preprocessing
- Dummy variables of reference year
- Lagged value
- BoxCox Transformation for Unemployment Rate
- Remove outlier

## 🧠 Feature Selection & Models
Feature Selection
![image](https://github.com/user-attachments/assets/2deab582-4210-4dea-8230-4f77695dd8a7)

## 🧪 Results
Our Linear Regression with Backward Selection Model predicted the U.S. Unemployment Rate for December 2024 is 4.14%. The 95% Confidence Interval is [4.0227%, 4.2696%]

![image](https://github.com/user-attachments/assets/bab18e09-2bc7-44be-8d44-089d077065d7)

## 📊 Evaluation Metrics
![image](https://github.com/user-attachments/assets/f5a8188a-064c-4f9c-9bb8-854244bbf9dc)

## 📌 Limitation & Future Improvement
- We focused on the accuracy of prediction and we believe there is a room for improvement on model 
interpretability, consider treating the multicollinearity using any other method like Ridge Regression, 
PCA in the future

## How to Run
Run notebook Regression.py first before running the primary notebook

## 📬 Contact
Feel free to reach out if you want to collaborate or ask questions!

