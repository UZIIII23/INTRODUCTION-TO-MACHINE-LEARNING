## Machine Learning Lab 5 : AEP Dataset Preprocessing and Feature Engineering

Overview:

This repository contains the implementation of data preprocessing and feature engineering techniques on the **AEP (American Electric Power)** time-series dataset. The notebook demonstrates dataset splitting, normalization, one-hot encoding, cyclic feature encoding, and preparation of training, validation, and testing datasets for machine learning models.

### Author:

* Uzair-ur-Rehman
* Registration No: 22JZELE0471
* Department: Electrical Engineering

Repository Contents:

Lab_5_22jzele0471.ipynb

Objectives:

* Load and preprocess the AEP dataset.
* Split the dataset into training, validation, and testing sets.
* Normalize numerical features using MinMaxScaler.
* Apply One-Hot Encoding to categorical features.
* Generate cyclic features using sine and cosine transformations.
* Create feature-rich datasets for machine learning and deep learning models.

Preprocessing Pipeline:

The notebook performs the following preprocessing steps:

* Train, Validation, and Test Split (70% / 20% / 10%)
* Min-Max Normalization
* One-Hot Encoding
* Cyclic Feature Engineering
* Feature Combination
* Export Processed Datasets to CSV

Feature Engineering:

The final processed dataset contains **21 features**, including:

* Normalized AEP Load
* Holiday Encoding
* Weekend Encoding
* Sine and Cosine of Month
* Sine and Cosine of Day of Week
* Sine and Cosine of Hour
* Seasonal Cyclic Features
* Sine and Cosine of Year Day

Technologies Used:

* Python
* Pandas
* NumPy
* Scikit-learn
* Pickle
* Jupyter Notebook

How to Run:

1. Clone the repository.
2. Install the required libraries:
3. Launch Jupyter Notebook:
4. Run: Lab_5_22jzele0471.ipynb

Learning Outcomes:

* Understand preprocessing techniques for time-series datasets.
* Perform dataset normalization using MinMaxScaler.
* Apply One-Hot Encoding for categorical variables.
* Generate cyclic representations for temporal features.
* Prepare machine learning-ready datasets for forecasting models.

License:

This project is submitted for academic and educational purposes.

