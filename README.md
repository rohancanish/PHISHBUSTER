

# 🛡️ PhishBuster: AI-Based Phishing Detection System

PhishBuster is an AI-powered phishing detection tool designed to help users identify and avoid fraudulent websites, emails, and messages. It uses machine learning and natural language processing (NLP) to classify URLs and text as phishing or safe with high accuracy.

---

## 🚀 Features

- ✅ Real-time phishing detection
- 🔍 URL and text input analysis
- 🧠 Trained ML model on phishing datasets
- 🖥️ Simple and interactive web interface
- 📦 Easily integrable into browsers or email clients

---

## 🛠️ Tech Stack

- Python 3
- Scikit-learn / XGBoost
- Pandas, NumPy
- Streamlit / Flask (for UI)
- Joblib / Pickle (for model storage)

---

## 📁 Project Structure

```

PhishBuster/
├── data/                # Datasets used for training
├── models/              # Trained ML models
├── app.py               # Web app interface
├── train\_model.ipynb    # Model training notebook
├── utils.py             # Helper functions
├── README.md            # Project overview

```

---

## ⚙️ How It Works

1. Input a suspicious URL or message into the web interface.
2. PhishBuster extracts features using custom rules and NLP.
3. The ML model predicts whether it’s phishing or safe.
4. The result is shown to the user with a confidence score.

---

## 📚 Dataset

Used datasets such as:
- [Phishing Website Dataset](https://www.kaggle.com/datasets/eswarchandt/phishing-website-detector)
- [Email Phishing Datasets](https://www.kaggle.com/datasets)

---

## 🚦 Example Use Cases

- ✅ A user checks if an unknown link is safe before clicking.
- 📧 Email service providers can use it to flag malicious emails.
- 🛡️ Companies can integrate it for employee security awareness.

---

## 📈 Future Scope

- Browser extension integration
- Real-time email scanning
- SMS phishing (smishing) detection
- Dashboard for phishing trends

---

## 👤 Author

**Rohan C Anish**  
Intern @ Emvigo Technologies  
[GitHub: rohancanish](https://github.com/rohancanish)

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

```

