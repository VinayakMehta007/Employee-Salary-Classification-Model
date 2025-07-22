# 💰 Employee Salary Classification App

This project predicts whether an individual's income is more than \$50K/year based on demographic data using Machine Learning. The web app is built using **Streamlit** and allows both single and batch prediction (via CSV upload). It was developed and deployed in **Google Colab** using the `pyngrok` library to expose the app publicly.

---

## 📌 Problem Statement

Predicting salary categories is a valuable task for HR analytics, economic studies, and workforce management. This app classifies whether a person earns `>50K` or `<=50K` using the **UCI Adult Income Dataset**. The classification is based on features like education, occupation, age, gender, etc.

---

## ⚙️ System Approach

### ✅ System Requirements

- Google Colab (or local Python environment)
- Python 3.8+

### ✅ Required Libraries

- `pandas`
- `numpy`
- `scikit-learn`
- `streamlit`
- `pyngrok`
- `joblib`

---

## 📊 Algorithm & Deployment

1. **Data Loading**: UCI Adult dataset is loaded and preprocessed.
2. **Feature Engineering**: Encoding categorical variables, removing nulls, and scaling.
3. **Model Building**: Trained a `RandomForestClassifier`.
4. **Model Saving**: The model is saved using `joblib`.
5. **Streamlit App**:
    - Single input prediction using form
    - Batch prediction using CSV file upload
6. **Deployment**: Hosted using `pyngrok` for live access in Google Colab.

---

## ✅ Features

- 🎯 Predict if income is `>50K` or `<=50K`
- 📁 Upload CSV for batch predictions
- 📊 Displays model confidence
- 🖥️ Intuitive Streamlit web interface
- 🚀 Hosted directly from Google Colab

---

## 📈 Future Scope

- Improve model with deep learning techniques (e.g., Neural Networks)
- Integrate database for storing user data
- Add explainability using SHAP or LIME
- Add role-based access control for admin and users

---

## 📚 References

- [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [Google Colab](https://colab.research.google.com/)

---


