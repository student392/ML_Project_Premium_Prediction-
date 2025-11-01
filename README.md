# ML-Premium-Prediction-

This project is a Machine Learning-based Premium Prediction App built using Streamlit for the frontend and a trained XGBoost model for predicting insurance premiums (or any other pricing-based outcomes).

## Features:-
Interactive Streamlit web interface.<br>
Predicts premium values using XGBoost.<br>
Clean and efficient data preprocessing with
pandas and numpy.<br>
Model training and evaluation using scikit-learn.<br>
Model persistence handled with joblib.<br>

## Technologies Used:-
### Library	Version	Purpose<br>
joblib	1.3.2	Saving and loading trained ML models<br>
pandas	2.0.2	Data manipulation and preprocessing<br>
streamlit	1.22.0	Web app framework for interactive UI<br>
numpy	1.25.0	Numerical computations<br>
scikit-learn	1.3.0	Model training, metrics, and preprocessing<br>
xgboost	2.0.3	Gradient boosting model for prediction<br>

## Model Training:-
The dataset is cleaned and preprocessed using pandas and numpy.
The model is trained using XGBoost for high accuracy.
Evaluation metrics like RMSE, MAE, and R² are used.
The final model is saved as model.joblib.
