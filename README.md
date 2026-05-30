# Surgical Patient Flow Intelligence (ML Case Study)
https://ankushshrikhande.github.io/Surgical-Patient-Flow-Intelligence-Multi-Task-ML-for-Healthcare-Operations/

###

Here you can find interesting INTERACTIVE EDA Dashboard  

https://ankushshrikhande.github.io/Surgical-Patient-Flow-Intelligence-Multi-Task-ML-for-Healthcare-Operations/eda_dashboard.html
#### notebook Link 

https://drive.google.com/file/d/1_LE1f9cZhCo4syOOv8oAwmE2C5VxllTL/view?usp=sharing

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


## Clinical Recommendations Dataset

Clinical Recommendation Engine Output Dataset

This dataset represents the output of a multi-task machine learning framework designed to support perioperative decision-making. Each row corresponds to a patient-level prediction instance, combining risk scores with actionable recommendations.

Key Features:
- Risk predictions: readmission probability, discharge readiness
- Operational signals: ICU requirement, social barriers, care plan completion
- AI-driven recommendations: mobility escalation, pain management optimization, post-discharge follow-ups, and care coordination

Purpose:
To bridge predictive analytics with clinical decision-making by generating interpretable, actionable interventions that can reduce length of stay, improve discharge efficiency, and minimize readmissions.


### Click here for  🏗️ [Production Architecture](https://ankushshrikhande.github.io/Surgical-Patient-Flow-Intelligence-Multi-Task-ML-for-Healthcare-Operations/architecture/production%20architecture.html)

### Click here for 🔄 [Data Pipeline Architecture](https://ankushshrikhande.github.io/Surgical-Patient-Flow-Intelligence-Multi-Task-ML-for-Healthcare-Operations/architecture/data%20pipeline%20architecture.html)



