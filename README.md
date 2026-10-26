# 💳 Credit Risk Prediction — Fraud Detection

A machine learning project that detects fraudulent financial transactions using a trained classification pipeline, with an interactive **Streamlit** web app for real-time prediction.

---

## 🚀 Project Overview

Financial fraud costs billions of dollars every year. This project builds a robust fraud detection system trained on a large real-world transaction dataset. The model identifies whether a given transaction is **fraudulent** or **legitimate** based on key transaction features.

---

## 📁 Project Structure

```
credit_risk_prediction/
├── fraud_detection.py                        # Streamlit web app
├── fraud_detection_analysis_and_model.ipynb  # EDA + model training notebook
├── fraud_detection_pipeline.pickle           # Trained ML pipeline
├── Fraud.csv                                 # Dataset (raw transactions)
└── README.md
```

---

## 🧠 Features Used

| Feature            | Description                        |
|--------------------|------------------------------------|
| `type`             | Type of transaction                |
| `amount`           | Transaction amount                 |
| `oldbalanceOrg`    | Sender's balance before transaction|
| `newbalanceOrig`   | Sender's balance after transaction |
| `oldbalanceDest`   | Receiver's balance before          |
| `newbalanceDest`   | Receiver's balance after           |

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data manipulation
- **Scikit-learn** — ML pipeline & model training
- **Streamlit** — interactive web UI
- **Joblib** — model serialization
- **Jupyter Notebook** — EDA & experimentation

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Akashsh-23/credit_risk_prediction.git
cd credit_risk_prediction
```

### 2. Install dependencies
```bash
pip install streamlit pandas scikit-learn joblib
```

### 3. Launch the Streamlit app
```bash
streamlit run fraud_detection.py
```

---

## 📊 Model Performance

The model was trained on over **6 million** transaction records. The pipeline includes:
- Feature encoding for transaction type
- Scaling / preprocessing
- A classification model (see notebook for full details)

---

## 📝 Author

**Akash** — [@Akashsh-23](https://github.com/Akashsh-23)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
