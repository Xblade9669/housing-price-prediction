# Housing Price Prediction

This project focuses on predicting housing prices based on various features using machine learning. The dataset used for this model was sourced from Kaggle. The goal is to predict the price of a house given several features such as location, size, and other relevant attributes.

## Project Overview

In this project, I performed the following steps:

1. **Data Preprocessing:**
   - I applied feature scaling to ensure that the features are on the same scale for the model.
   - Both numerical and categorical features were handled using encoding techniques:
     - **Numerical Encoding:** For numerical features, I used standard scaling to normalize them.
     - **One-Hot Encoding:** Categorical features were converted to numerical form using one-hot encoding.
   - I used pipelines to streamline these preprocessing steps and ensure that they were applied consistently to the training and testing data.

2. **Model Building:**
   - I created the model using a Random Forest Regressor, which is a powerful machine learning algorithm for regression tasks.
   - The model was trained and tested using cross-validation to ensure reliable performance.

3. **Kaggle Submission:**
   - This notebook was also submitted to Kaggle, where the dataset originated.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- RandomForestRegressor

## Dataset

The dataset was sourced from Kaggle playground and contains various features related to housing prices. The dataset was split into training and testing sets, and after preprocessing, the Random Forest model was used to predict housing prices.


