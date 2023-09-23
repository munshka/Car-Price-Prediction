# Car-Price-Prediction

This repository is dedicated to predicting car prices based on a dataset from CarDekho. The dataset contains information about various car attributes, such as name, year, selling price, kilometers driven, fuel type, seller type, transmission, and owner history.

## Dataset
You can access the dataset used in this project via this [link](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho).

## Workflow Overview
Here is a brief description of the steps taken in this project:

1. **Imputing Missing Values**: We handled missing values in the 'km_driven' column by filling them with the mean.

2. **Encoding Categorical Features**: Categorical features like 'name' and 'transmission' were encoded for machine learning algorithms.

3. **Oversampling**: To address class imbalance, we oversampled underrepresented selling price categories.

4. **Feature Scaling**: We used scaling techniques (MinMax and Standard scaling) to standardize the feature values.

5. **Model Training**: Several models were trained on the scaled data.

6. **Model Evaluation**: The model's performance was evaluated using accuracy metrics.

7. **Feature Selection**: Relevant features were selected for model training.

8. **Train-Test Split**: The dataset was divided into training and testing sets to assess the model's performance.

This project aims to predict car prices using machine learning techniques after data preprocessing and feature engineering.
