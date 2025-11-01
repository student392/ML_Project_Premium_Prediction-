# ML-Premium-Prediction-

This project is a Machine Learning-based Premium Prediction App built using Streamlit for the frontend and a trained XGBoost model for predicting insurance premiums (or any other pricing-based outcomes).

## Features:-
Interactive Streamlit web interface.
Predicts premium values using XGBoost.
Clean and efficient data preprocessing with
pandas and numpy.
Model training and evaluation using scikit-learn.
Model persistence handled with joblib.

## Technologies Used:-
Library	Version	Purpose
joblib	1.3.2	Saving and loading trained ML models
pandas	2.0.2	Data manipulation and preprocessing
streamlit	1.22.0	Web app framework for interactive UI
numpy	1.25.0	Numerical computations
scikit-learn	1.3.0	Model training, metrics, and preprocessing
xgboost	2.0.3	Gradient boosting model for prediction

## Model Training:-
The dataset is cleaned and preprocessed using pandas and numpy.
The model is trained using XGBoost for high accuracy.
Evaluation metrics like RMSE, MAE, and R² are used.
The final model is saved as model.joblib.