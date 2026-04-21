❤️ Heart-Stroke-Prediction
ML-based Heart Disease Prediction system using KNN with an interactive Streamlit web app for real-time risk analysis.


📌 Overview
This project is a Machine Learning-based web application that predicts the risk of heart disease using patient health data. It uses a trained KNN (K-Nearest Neighbors) model and provides an interactive UI built with Streamlit.


🚀 Features
- Predicts heart disease risk (High / Low)
- Interactive user interface using Streamlit
- Real-time prediction
- Preprocessing with scaler
- Encoded categorical inputs handled properly


🛠️ Tech Stack
- Python 
- Pandas
- matplotlib.pyplot
- seaborn
- Scikit-learn
- Streamlit
- Joblib


📂 Project Structure
heart-stroke-prediction/

├── app.py
├── heart_proj.ipynb
├── KNN_heart.pkl
├── heart_scaler.pkl
├── heart_columns.pkl
├── requirement.txt
└── README.md


▶️ How to Run the Project

1. Clone the repository
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction

2. Install dependencies
pip install -r requirements.txt

3. Run the Streamlit app
streamlit run app.py


📊 Input Features
-Age
-Sex
-Chest Pain Type
-Resting Blood Pressure
-Cholesterol
-Fasting Blood Sugar
-Resting ECG
-Max Heart Rate
-Exercise Induced Angina
-Oldpeak
-ST Slope


🎯 Output
-✅ Low Risk of Heart Disease
-⚠️ High Risk of Heart Disease
