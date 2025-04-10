🩺 DIABETES PREDICTION USING LOGISTIC REGRESSION
=============================================

📌 Project Overview:
-------------------
This project is a **binary classification** model that predicts whether a patient has diabetes or not using **Logistic Regression**. The model is trained on medical data that includes key health indicators.

📊 Features Used:
----------------
The dataset includes the following features:

1️⃣ age                 - Age of the patient  
2️⃣ hypertension        - 1 if the patient has hypertension, 0 otherwise  
3️⃣ heart_disease       - 1 if the patient has any heart disease, 0 otherwise  
4️⃣ bmi                 - Body Mass Index of the patient  
5️⃣ HbA1c_level         - Hemoglobin A1c level (indicator of blood sugar control)  
6️⃣ blood_glucose_level - Current blood glucose level  
7️⃣ diabetes            - 🎯 Target variable (1: diabetic, 0: non-diabetic)  

⚙️ Steps to Run:
----------------
1. 🧰 **Install required libraries:**
   - `pandas`
   - `numpy`
   - `scikit-learn`

2.🧹 Load and preprocess the data:
Handle missing values if any.
Standardize numerical features using StandardScaler.
🧠 Train the model:
Use LogisticRegression from sklearn.linear_model
Perform train-test split (e.g., 80/20)
📈 Evaluate the model:
✅ Accuracy
🔲 Confusion Matrix
🧮 Precision, Recall, F1-Score


🚀 Usage:

The model can be used to predict diabetes status based on a patient's medical attributes. It's ideal for early diagnosis and screening in healthcare applications.


🔧 Future Improvements:

🌐 Deploy model via Flask / FastAPI / Streamlit
📈 Improve dataset balance and size
🌲 Test advanced models like Random Forest or XGBoost

