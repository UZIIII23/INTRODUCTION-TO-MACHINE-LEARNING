## Machine Learning Lab 12 :  LSTM for Time Series Forecasting

Overview:

This repository contains the implementation of a Long Short-Term Memory (LSTM) neural network for multivariate time series forecasting. The notebook demonstrates data preprocessing, model development, training, fine-tuning, prediction, and performance evaluation using the AEP power consumption dataset.

### Author:

* Uzair-ur-Rehman  
* Registration No: 22JZELE0471  
* Department:  Electrical Engineering  

Repository Contents:

Lab_12_22jzele0471.ipynb

Objectives:

* Build an LSTM model for time-series forecasting.
* Learn sequence modeling using recurrent neural networks.
* Train and validate the model.
* Fine-tune the trained model for improved performance.
* Predict future values and evaluate forecasting accuracy.

Model Overview:

The model consists of:

* Input Layer
* LSTM Layer (8 Units)
* LSTM Layer (20 Units)
* Flatten Layer
* Dense Output Layer

Evaluation Metrics:

The model is evaluated using:

* Mean Absolute Error (MAE)
* Median Absolute Error (MedAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)
* Median Absolute Percentage Error (MDAPE)

Fine-Tuning:

The trained LSTM model is fine-tuned by:

* Loading the best saved checkpoint.
* Reducing the learning rate.
* Training for additional epochs.
* Saving the best-performing model based on validation loss.

Technologies Used:

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

How to Run:

1. Clone the repository.
2. Install required libraries:
3. Launch Jupyter Notebook:
4. Run: Lab_12_22jzele0471.ipynb

Learning Outcomes:

* Understand LSTM networks for sequential data.
* Prepare time-series datasets for forecasting.
* Train and fine-tune deep learning models.
* Evaluate forecasting performance using regression metrics.
* Compare LSTM-based forecasting with other neural network models.

License:

This project is submitted for academic and educational purposes.
