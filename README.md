# FairAI – Bias Detection & Correction System

FairAI is an AI-powered platform that detects, explains, and mitigates bias in automated decision-making systems. It enables organizations to build fair, transparent, and responsible AI models, particularly in sensitive domains like hiring.

---

##  Problem Statement

AI systems used in hiring and decision-making often inherit biases from historical data. These biases can lead to unfair outcomes, such as discrimination based on gender, background, or other sensitive attributes.

FairAI addresses this challenge by providing an end-to-end pipeline to:
- Detect bias
- Explain why it occurs
- Mitigate it effectively

---

##  Solution Overview

FairAI analyzes datasets and model predictions to identify disparities across different groups (e.g., gender). It then applies fairness-aware techniques to reduce bias while maintaining model performance.

The platform provides:
-  Bias metrics (Demographic Parity, Equal Opportunity)
-  Visual dashboards
-  AI-generated explanations
-  Bias mitigation with before vs after comparison

---

##  Key Features

- **Bias Detection**
  - Calculates fairness metrics such as:
    - Demographic Parity Gap
    - Equal Opportunity Gap

- **Explainable AI**
  - Uses SHAP-based feature importance
  - AI-generated insights (Google Gemini)

- **Bias Mitigation**
  - Applies fairness constraints using Fairlearn
  - Reduces discrimination while preserving accuracy

- **Before vs After Comparison**
  - Visual and numerical comparison of model fairness

- **Interactive Dashboard**
  - Clean UI with charts and insights

---

##  Demo Workflow

1. Upload dataset or use sample hiring data  
2. Select target and sensitive attribute  
3. Analyze bias  
4. View fairness metrics and charts  
5. Apply mitigation  
6. Compare results (before vs after)  

---

##  Sample Use Case

A hiring dataset with gender bias:
- Before mitigation:
  - High bias (Parity Gap: 34%)
- After mitigation:
  - Fair model (Parity Gap: 5%)
  - Minimal accuracy drop (~1.6%)

---

##  Tech Stack

### Frontend
- React.js
- Chart.js

### Backend
- Python (FastAPI / Flask)

### Machine Learning
- Scikit-learn
- Fairlearn
- SHAP

### AI Integration
- Google Gemini API (for explanations)

### Deployment
- Google Cloud (Cloud Run / Firebase)

---

## 📁 Project Structure
