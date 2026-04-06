# Healthcare Insurance Claim Denial Predictor

## 📌 Project Overview
This project uses Machine Learning to predict whether a healthcare insurance claim will be **Approved or Denied** before submission. It helps hospitals reduce claim rejections and improve revenue management.

---

## 🚀 Objective
- Predict claim denial probability
- Identify high-risk claims
- Reduce errors before submission
- Support data-driven decision making

---

## 📊 Dataset
- Records: ~15,000
- Features: 16
- Target: `is_claim_denied` (Approved / Denied)

### Key Features
- patient_age_years
- patient_gender
- insurance_plan_type
- is_in_network
- procedure_code_cpt
- primary_diagnosis_code_icd10
- billed_amount_usd
- prior_auth_required
- days_between_service_and_submission

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit (for UI)

---

## 🔄 Data Preprocessing
- Handled missing values
- Encoded categorical features
- Feature scaling using StandardScaler
- Train-test split

---

## 🤖 Models Used
- Logistic Regression
- Decision Tree
- Random Forest (Best Model)

---

## 📈 Model Performance
- Best Model: Random Forest
- Accuracy: 77%
- Metrics: Precision, Recall, F1-Score

---

## 💡 Key Insights
- Early prediction reduces claim denials
- False negatives need improvement
- Model helps in better decision-making

---

## 🖥️ Demo Output# claim-AI
This project builds a machine learning model to predict whether a healthcare insurance claim will be approved or denied before submission. Using patient, billing, and policy data, the model identifies high-risk claims, helping reduce errors, minimize denials, and improve hospital revenue and decision-making efficiency.
