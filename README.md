# 🏠 House Price Prediction using Ensemble Learning (Task-5)

## 📌 Project Overview

This project focuses on applying **Ensemble Learning techniques** to improve the performance of machine learning models for predicting housing prices.

The goal is to build a **real-world ML pipeline** using advanced models like:

- Random Forest (Bagging)
- Gradient Boosting (Boosting)

and compare their performance.

---

## 📊 Dataset

Dataset Used: **California Housing Dataset**

Features include:

- MedInc (Median Income)
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

### 🎯 Target Variable

- **Housing_Value** → Median house value

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🧠 Machine Learning Workflow

1. Data Loading  
2. Data Preprocessing  
3. Train-Test Split  
4. Model Training  
5. Model Evaluation  
6. Hyperparameter Tuning  
7. Feature Importance Analysis  
8. Model Comparison  

---

## 🤖 Models Implemented

### 1️⃣ Random Forest Regressor
- Ensemble model using **Bagging**
- Reduces overfitting
- Provides stable predictions

### 2️⃣ Gradient Boosting Regressor
- Ensemble model using **Boosting**
- Learns from previous errors
- Captures complex patterns effectively

---

## 📈 Model Performance

| Model | R² Score |
|------|---------|
| Random Forest | 0.7748 |
| **Gradient Boosting** | **0.8292 🔥** |

---

## 🏆 Best Model

**Gradient Boosting Regressor** achieved the highest performance.

### Key Observations:

- Higher accuracy compared to Random Forest  
- Better at capturing complex relationships  
- Learns sequentially from previous errors  

---

## 📊 Feature Importance

Feature importance was analyzed using Random Forest to understand which features impact housing prices the most.

Key influencing features:
- Median Income (MedInc)
- Location (Latitude & Longitude)

---

## ⚙️ Hyperparameter Tuning

GridSearchCV was used to optimize model parameters and improve performance.

Example parameters tuned:
- n_estimators  
- max_depth  

---

## 🔄 Machine Learning Pipeline

A pipeline was used to automate preprocessing and modeling:

- Data scaling
- Model training

This ensures a clean and reproducible workflow.

---

## 🚀 Key Learnings

- Understanding of Ensemble Learning  
- Difference between Bagging and Boosting  
- Importance of model optimization  
- Feature importance interpretation  
- Building real-world ML pipelines  

---

## 📂 Project Structure
```
Task-5/
│
├── notebook.ipynb
├── README.md
├── California_housing.csv
```
