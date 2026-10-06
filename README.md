# Customer Churn Prediction using Artificial Neural Networks (ANN)

An end-to-end Machine Learning web application that predicts whether a bank customer is likely to churn (exit) based on their demographic, financial, and account information. Built with TensorFlow/Keras, Scikit-learn, and Streamlit.

---

## 🚀 Features
- **Deep Learning Model:** Artificial Neural Network (ANN) trained on bank customer churn data with early stopping and learning rate scheduling.
- **Data Preprocessing Pipeline:** Automated categorical encoding (One-Hot Encoding for Geography, Label Encoding for Gender) and Feature Scaling (StandardScaler).
- **Interactive Web App:** Real-time prediction dashboard built with Streamlit providing churn risk probabilities, metrics, and actionable retention recommendations.
- **Jupyter Notebooks:** Includes experimental training workflows (`experiments.ipynb`) and modular inference testing (`prediction.ipynb`).

---

## 🛠️ Project Structure
```text
├── app.py                     # Streamlit web application
├── prediction.ipynb           # Inference pipeline notebook
├── experiments.ipynb          # Model training & experiment tracking
├── Churn_Modelling.csv        # Dataset
├── model.h5                   # Trained Keras ANN model
├── label_encoder_gender.pkl   # Serialized LabelEncoder for Gender
├── onehot_encoder_geo.pkl     # Serialized OneHotEncoder for Geography
├── scaler.pkl                 # Serialized StandardScaler
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
```

---

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Debarghapaulgh/customer-churn-prediction-ann.git
   cd customer-churn-prediction-ann
   ```

2. **Create and activate a virtual environment:**
   ```bash
   conda create -p venv python=3.11 -y
   conda activate ./venv
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🌐 Running the Streamlit App

Launch the dashboard locally:
```bash
streamlit run app.py
```

Access the app in your browser at `http://localhost:8501`.
