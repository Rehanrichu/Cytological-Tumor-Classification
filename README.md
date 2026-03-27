# Cytological Tumor Classification

A simple Machine Learning project that classifies tumors as **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using cellular features.

---

# Overview

This project uses a **Random Forest Classifier** to analyze cytological data (cell characteristics like radius, texture, area, etc.) and predict whether a tumor is cancerous.

It is built using concepts from:

* Kaggle *Intro to Machine Learning*
* Python fundamentals

---

## Features

* Data handling with **Pandas**
* Model training using **Random Forest**
* Train-test split for proper validation
* Feature importance analysis
* Simple prediction function
* Model saving with `joblib`

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib & Seaborn

---

## ▶️ How to Run

```bash
pip install pandas scikit-learn matplotlib seaborn joblib
python tumor_classifier.py
```
---

## 🧪 Output

* Model accuracy and classification report
* Top important features visualization
* Sample prediction (Malignant / Benign)
---
## 📌 Future Improvements

* Add Streamlit web interface
* Hyperparameter tuning
* Better dataset / real-world data integration

---
