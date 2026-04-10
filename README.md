# e-commerce_ML

## 📌 Project Overview
This project aims to predict whether a customer will make a purchase based on their browsing behavior and session details using Machine Learning.

---

## 🎯 Problem Statement
The objective is to classify customers into two categories:
- 0 → Not Purchase
- 1 → Purchase

This helps businesses improve conversion rates and target potential customers.

---

## 📊 Dataset
A synthetic dataset of 5000 rows was generated with the following features:

- Age  
- Session_Duration  
- Pages_Viewed  
- Product_Price  
- Previous_Purchases  
- Discount_Applied  
- Gender  
- Device_Type  
- Purchase (Target)

---

## ⚙️ ML Workflow
1. Data Cleaning  
2. Handling Missing Values  
3. Encoding Categorical Variables  
4. Feature Selection  
5. Train-Test Split (80-20)  
6. Model Training:
   - Logistic Regression
   - Decision Tree
   - Random Forest  
7. Model Evaluation  

---

## 🤖 Models Used
- Logistic Regression ✅ (Best)
- Decision Tree  
- Random Forest  

---

## 📈 Results

| Model | Accuracy |
|------|--------|
| Logistic Regression | 81.87% |
| Random Forest | 79.45% |
| Decision Tree | 69.98% |

---

## 📊 Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  

---

## 🔍 Key Insights
- Higher session duration increases purchase probability  
- More pages viewed → higher engagement  
- Discounts improve conversion rate  
- Returning customers are more likely to purchase  

---

## 🧪 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
