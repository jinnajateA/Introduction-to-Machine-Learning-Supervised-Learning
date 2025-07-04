# Peer-graded Assignment: DTSA 5509 Supervised Learning Final Project  

### Problem Definition

This project tackles a **supervised machine learning** task focused on predicting whether an individual is a **smoker or non-smoker** based on a set of physiological and behavioral health indicators. This is a **binary classification problem** where the model aims to learn patterns that help distinguish current smokers from those who have successfully quit or never smoked.

---

### Problem Description


Smoking is a major contributor to preventable diseases and premature mortality worldwide. Being able to identify smoking status using passive physiological signals could have significant implications in preventive healthcare and wellness monitoring.

In this project, we utilize a dataset of bio-signals to predict the smoking status of individuals. The machine learning model should detect underlying patterns in the data that are indicative of smoking behavior.


---

### Problem Topic

- **Type of Learning**: Supervised Learning  
- **Task Type**: Binary Classification  
- **Target Variable**: `smoking_status` (0 = Non-Smoker, 1 = Smoker)  
- **Evaluation Metrics**: Accuracy, F1 Score, ROC-AUC

---

### About the Data

The dataset comes from the [Kaggle Playground Series - Season 3, Episode 24](https://www.kaggle.com/competitions/playground-series-s3e24/overview) and consists of structured tabular data with a wide range of features derived from routine medical examinations.

#### Features Overview:
- **Demographics**:
  - `Age` (in 5-year intervals)
  - `Height` (cm)
  - `Weight` (kg)
  - `Waist circumference` (cm)

- **Vision & Hearing**:
  - `Eyesight (left)`
  - `Eyesight (right)`
  - `Hearing (left)`
  - `Hearing (right)`

- **Vital Signs & Lab Tests**:
  - `Systolic blood pressure`
  - `Diastolic blood pressure`
  - `Fasting blood sugar`
  - `Total cholesterol`
  - `Triglyceride`
  - `HDL cholesterol`
  - `LDL cholesterol`
  - `Hemoglobin`
  - `Urine protein`
  - `Serum creatinine`
  - `AST` (glutamic oxaloacetic transaminase)
  - `ALT` (glutamic oxaloacetic transaminase)
  - `GTP (γ-GTP)`

- **Other**:
  - `Dental caries`

- **Target**:
  - `Smoking status` — 0 for non-smoker, 1 for smoker

#### Data Type:
- All features are **numerical** (continuous or categorical encoded numerically)  
- Format: **Tabular**
- Estimated size: ~160,000 samples

---

> **Source**:  
> Kaggle. (2024). *Playground Series - Season 3, Episode 24*. Retrieved from https://www.kaggle.com/competitions/playground-series-s3e24/overview
