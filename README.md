
# 🏥 Health Insurance Cost Predictor

This is a Machine Learning-powered web application built with **Streamlit** that predicts the cost of health insurance based on various user inputs like age, BMI category, income, medical history, and more.

## 🔍 Features

- User-friendly UI using Streamlit
- Predicts insurance costs using a trained ML model
- Includes categorical & numerical input fields
- Fully deployable on Streamlit Cloud

## 📊 Input Fields

- Age
- Number of Dependants
- Income (in Lakhs)
- Genetical Risk Score
- Insurance Plan
- Employment Status
- Gender
- Marital Status
- BMI Category
- Smoking Status
- Region
- Medical History

## 🧠 Model Used

- Trained using **XGBoost** and **Scikit-learn**
- Saved and loaded using `joblib`

## 🚀 How to Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/health-insurance-predictor.git
   cd health-insurance-predictor
   ```

2. **Create and activate a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**

   ```bash
   streamlit run main.py
   ```

## 📁 Project Structure

```
├── artifacts/
│   └── model.rest.joblib         # Trained model file
├── main.py                       # Streamlit frontend
├── prediction_helper.py          # Prediction logic
├── requirements.txt              # Python dependencies
└── README.md
```

## 🛠 Tech Stack

- Python
- Streamlit
- XGBoost
- Scikit-learn
- Pandas
- Joblib

## 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

