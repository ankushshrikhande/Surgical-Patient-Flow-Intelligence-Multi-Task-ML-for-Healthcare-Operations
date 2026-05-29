# Surgical Patient Flow Intelligence (ML Case Study)
https://ankushshrikhande.github.io/Surgical-Patient-Flow-Intelligence-Multi-Task-ML-for-Healthcare-Operations/

https://ankushshrikhande.github.io/eda_dashboard.html/

## 📖 Overview
This project builds a **multi-task, real-time machine learning system** to support perioperative and postoperative decision-making for surgical inpatients.

The system predicts:
- ✅ Discharge readiness (patient-day level)
- ✅ Length of Stay (LOS)
- ✅ 30-day readmission risk  
- ✅ Recommended interventions

---

## 🎯 Objectives

- Predict discharge readiness dynamically
- Forecast LOS at admission and post-operation
- Identify readmission risk
- Recommend interventions to optimize outcomes

---

## 🏥 Business Impact

This system helps hospitals:
- Improve **bed management & OR scheduling**
- Reduce **delayed discharges**
- Lower **avoidable readmissions**
- Align **clinical decisions with operations**

---

## 🧠 Modeling Approach

We design a **multi-task learning framework**:

### Option 1: Shared Backbone Model
- Common feature encoder
- Task-specific heads:
  - Classification (readmission, discharge readiness)
  - Regression (LOS)

### Option 2: Coordinated Models
- Separate models per task
- Shared feature store

---

## 📊 Dataset

Synthetic dataset stored in:

### Tables:
- `patients`
- `surgical_encounters`
- `daily_clinical_status`
- `outcomes`
- `hospital_operations_daily`

