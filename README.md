# Customer Churn Analysis and Prediction

## Project Overview
This project predicts whether a customer is likely to leave a service (churn) using Machine Learning. A Streamlit web application allows users to enter customer details and receive a churn prediction.

## Objectives
- Analyze customer information related to churn.
- Preprocess customer data for Machine Learning.
- Train and evaluate classification models.
- Build an interactive web application using Streamlit.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib

## Features
- Accepts customer age, gender, tenure, and monthly charges.
- Applies the saved scaler to input data.
- Uses a trained Machine Learning model to predict churn.
- Displays the prediction through a simple web interface.

## Input Features
- Age
- Gender
- Tenure
- Monthly Charges

## Project Structure
```text
Customer-Churn-Analysis-Prediction/
├── app.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

4. Open the local URL displayed in the terminal.

## Note
The application requires the trained model (`model.pkl`) and scaler (`scaler.pkl`) files to be available in the project directory.

