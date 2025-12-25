<h1 align="center">🎓 Career Path Prediction Using Machine Learning</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-green" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Classification-orange" />
  <img src="https://img.shields.io/badge/Status-Deployed-success" />
</p>

---

## 🌟 Overview  
This project predicts the **best career path** for a student based on soft skills, interests, and preferences.  
A custom dataset of **1100+ Google Form responses** was collected and processed into ML-ready format.  
A modern **FastAPI application** is included for real-time predictions.

---

## 🔥 Key Features  

✨ Collected **1100+ survey responses**  
✨ **13 categorical features** processed using Label Encoding  
✨ Trained multiple ML models:  
- Logistic Regression  
- Random Forest  
- XGBoost  
- SVM  
- KNN  

✨ Best accuracy: **~70% using Stacking Ensemble**  
✨ Fully working **FastAPI deployment** with HTML form  
✨ Clean folder structure + reproducible code

---

## 🧠 Machine Learning Workflow  

### **1️⃣ Data Collection**
- Google Forms  
- Real student responses  
- Soft-skill based questions  

### **2️⃣ Preprocessing**
- Removed inconsistent values  
- Label Encoding  
- Scaling using `StandardScaler`  
- Dataset cleaned for ML models  

### **3️⃣ Model Training**
The following ML models were tested:

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~62% |
| Random Forest | ~64% |
| XGBoost | ~67% |
| SVM | ~65% |
| KNN | ~60% |
| **Stacking Ensemble** | **~70% (Best)** |

### **4️⃣ Model Saving**
Saved using `joblib`:
- `stacking_model.pkl`  
- `scaler.pkl`  
- `label_encoder.pkl`  

### **5️⃣ Deployment**
FastAPI app includes:
- HTML form (`templates/`)  
- CSS styling (`static/`)  
- Backend preprocessing + prediction  

---

## 📁 Project Structure  

Career_Path_Prediction/
│
├── static/ # CSS files
├── templates/ # HTML templates
│
├── main.py # FastAPI backend
├── main.ipynb # Complete ML workflow
│
├── stacking_model.pkl # Saved ensemble model
├── scaler.pkl # Saved scaler
├── label_encoder.pkl # Output label encoder
│
├── smart_career_path_predict_dataset.csv # Dataset (1100+ entries)
├── requirements.txt # Dependencies
├── LICENSE
└── README.md

---

## 🚀 Running Locally  

## 1️⃣ Clone the repo
git clone https://github.com/Meghana303/Career_Path_Prediction.git
cd Career_Path_Prediction

## 2️⃣ Create a virtual environment
- python -m venv venv
- venv\Scripts\activate       # Windows
- source venv/bin/activate    # macOS/Linux

## 3️⃣ Install dependencies
pip install -r requirements.txt

## 4️⃣ Start FastAPI server
uvicorn main:app --reload

## 5️⃣ Open UI
http://127.0.0.1:8000

## 🌐 Deployment Notes

You can deploy this FastAPI app on:

Render

Railway

Heroku

AWS EC2

Local server

Ensure these files exist during deployment:

templates/

static/

stacking_model.pkl

scaler.pkl

label_encoder.pkl

Start command:

uvicorn main:app --host 0.0.0.0 --port $PORT

## 🛠 Tech Stack

Languages:

Python

HTML

CSS

Libraries:

Scikit-learn

XGBoost

Pandas

NumPy

FastAPI

Uvicorn

Jinja2

Tools:

VS Code

GitHub

Google Forms

## 🌱 Future Improvements

Add hyperparameter tuning

Add cross-validation

Build React/JS front-end

Deploy a full hosted demo

Expand dataset quality

## 👩‍💻 Author

Neeraj Reddy (Neerajreddi)
🔗 Github: https://github.com/neerajreddi

Meghana (Meghana303)
🔗 GitHub: https://github.com/Meghana303



---
