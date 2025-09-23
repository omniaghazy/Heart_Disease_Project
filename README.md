# Heart_Disease_Project

Heart Disease Prediction App
Project Overview
This project is a complete machine learning pipeline that predicts the presence of heart disease in patients based on their health data. The solution includes a machine learning model and a user-friendly web application built with Streamlit for easy interaction.

The main objective was to develop a robust and reliable prediction model and package it into a deployable application.

Project Deliverables
This repository contains all the key assets of the project:

Data: The raw and cleaned datasets (heart.csv, cleaned_data.csv).

Model: The final trained model pipeline saved in a .pkl format (final_pipeline.pkl).

Source Code: The Streamlit web application code (app.py).

Documentation: This README.md file and requirements.txt for environment setup.

Project Pipeline
1. Data Preprocessing
The raw dataset was cleaned to handle missing values and prepare the features for model training.

2. Feature Engineering & Selection
Advanced techniques like Principal Component Analysis (PCA) and manual feature selection were used to identify the most impactful features for the model, improving its performance and reducing complexity.

3. Model Training & Evaluation
Multiple machine learning algorithms, including Decision Tree and Random Forest, were trained and evaluated. The Random Forest model was selected as the final model due to its superior performance, specifically its high F1-Score.

4. Hyperparameter Tuning
Grid Search with Cross-Validation was performed to find the optimal hyperparameters for the Random Forest model, maximizing its predictive accuracy.

5. Streamlit Web UI Development
A web application was developed using Streamlit, allowing users to input their health data and receive a real-time prediction. The app also includes interactive data visualizations to compare user data with the original dataset.

6. Deployment
The Streamlit application was deployed using Ngrok, making it publicly accessible for live demonstration.

How to Run the App
To run this application, follow these steps:

Clone the repository:
git clone <repository_url>

Navigate to the project directory:
cd heart-disease-prediction

Install the required libraries:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

If you want to deploy it publicly, you can use Ngrok:
ngrok http 8501

Note: For Ngrok deployment, you may need to install it and set up your authentication token.

Author: coreX Team
