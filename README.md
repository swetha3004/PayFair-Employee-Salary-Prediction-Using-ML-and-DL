# PayFair-Employee-Salary-Prediction-Using-ML-and-DL

A smart Streamlit web app that predicts an employee's salary using machine learning and deep learning models based on metrics like age, gender, education, job title, and experience. The system also suggests skills to improve earning potential and includes a resume-upload option (demo).

---

## 🚀 Features

- 📊 Salary prediction using ML (XGBoost) and DL (Neural Network)
- 📄 Resume upload with dummy parser (spaCy + PDF)
- 💡 Personalized skill improvement suggestions
- 🧠 Optional SHAP visualizations for model explainability
- 🌐 Simple Streamlit frontend (form + upload support)

---

## 📦 Required Libraries

| Package        | Purpose                            |
|----------------|------------------------------------|
| `pandas`       | Data manipulation                  |
| `numpy`        | Numerical computations             |
| `matplotlib`   | Visualization                      |
| `seaborn`      | Visualization                      |
| `scikit-learn` | Preprocessing, model evaluation    |
| `xgboost`      | ML prediction model                |
| `tensorflow`   | DL prediction model (MLP)          |
| `streamlit`    | Web app frontend                   |
| `spacy`        | NLP for resume parsing             |
| `PyMuPDF`      | PDF text extraction                |
| `shap`         | Model explainability (optional)    |

To install all at once:
```bash
pip install -r requirements.txt

---

## 🧠 Steps Followed (Project Flow)

✅ Installed all required libraries  
📥 Collected and cleaned salary dataset  
🔠 Encoded categorical features (Gender, Education, Job Title)  
📏 Scaled numerical features (Age, Experience)  
🤖 Trained ML (XGBoost) and DL (MLP) models  
💾 Saved trained models with pickle  
🧠 Parsed dummy resume for user data (spaCy + PDF)  
💡 Compared user skills and recommended new ones  
🌐 Built a simple Streamlit web app  
🚀 Deployed via ngrok or locally  

---

## 📌 Future Improvements

- Use advanced NLP models (BERT, RoBERTa) for resume parsing  
- Connect to real-time job data sources  
- Deploy via Streamlit Cloud or AWS  
- Admin dashboard for HR teams  

---

## 🙌 Credits

Made with ❤️ using open-source tools like:

- [Streamlit](https://streamlit.io)  
- [XGBoost](https://xgboost.ai)  
- [spaCy](https://spacy.io)  
