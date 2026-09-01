
# Used Car Data Preprocessing

## Overview

This project focuses on preprocessing a Used Car Resale Dataset using Python and Pandas. The dataset is prepared for further analysis and machine learning by applying essential data preprocessing techniques.

## Objectives

- Identify and handle outliers using the IQR method
- Encode categorical variables
- Scale numerical features
- Separate features and target variable
- Split the dataset into training and testing sets
- Prevent data leakage during preprocessing
- Export the final preprocessed dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

## Preprocessing Steps

1. Loaded and inspected the Used Car Resale Dataset.
2. Separated the features from the target variable `Resale_Price_Lakh`.
3. Split the data into training and testing sets.
4. Detected and handled numerical outliers using the IQR method.
5. Encoded categorical variables using one-hot encoding.
6. Applied StandardScaler to numerical features.
7. Fitted preprocessing transformations only on the training data to prevent data leakage.
8. Verified the processed dataset.
9. Exported the preprocessed dataset as a CSV file.

## Dataset

The dataset contains 320 used-car records with information including:

- Car ID
- Brand
- Year
- Mileage
- Engine Capacity
- Power
- Fuel Type
- Transmission
- City
- Seller Type
- Condition
- Previous Owners
- Accidents Reported
- Service Score
- Resale Price

## Project Files

```text
Used-Car-Data-Preprocessing/
│
├── Used_Car_Data_Preprocessing.ipynb
├── Used_Car_Resale_Dataset.csv
├── preprocessed_used_car_dataset.csv
└── README.md
````

## Result

The raw used-car dataset was transformed into a processed, machine-learning-ready dataset through outlier handling, categorical encoding, feature scaling, and proper train-test preprocessing.

## Training Program

This project was completed as part of the **IDRA Data Science & AI Training Program 2026**.

## Author

**Abhinav Jacob Sunny**

