# 🏦 Bank Churn Analysis

**Project Period:** 2024/11 – 2025/2  
**Data Source:** Kaggle

---

## 🎯 Project Objective
This project aims to analyze the main factors contributing to bank customer churn and build a machine learning model to predict the likelihood of customer attrition.  
The goal is to help banks design retention strategies for high-risk customers.  

The LightGBM (LGB) algorithm was primarily used for model training, and **Feature Importance** was applied to identify the key drivers of churn.

---

## 📊 Feature Importance Analysis
According to the LightGBM feature importance ranking, the top factors influencing customer churn are:

1. **Balance** (Account Balance)  
2. **Credit Score**  
3. **NumComplaints** (Number of Complaints)  
4. **NumOfProducts** (Number of Products Held)

---

## 🔍 Analysis & Findings

### **Balance (Account Balance)**
- Customers with lower balances are more likely to churn, indicating a strong relationship between asset retention and loyalty.  
- High-balance customers are more likely to maintain long-term relationships with the bank.  
- **Recommendation:** Provide financial management services and incentives for low-balance customers.

### **Credit Score**
- Customers with lower credit scores are more prone to churn, possibly due to loan product eligibility, interest rates, and promotional offers.  
- **Recommendation:** Develop services or educational programs aimed at improving credit scores for at-risk customers.

### **NumComplaints (Number of Complaints)**
- A higher number of complaints correlates with a higher churn risk, reflecting the link between customer satisfaction and retention.  
- **Recommendation:** Improve customer service quality and response times to minimize negative experiences.

### **NumOfProducts (Number of Products Held)**
- Customers with fewer products (e.g., only a single account or service) have higher churn risk.  
- **Recommendation:** Encourage cross-selling to increase product diversity and customer engagement.

---

## 📌 Summary & Recommendations
- **High-balance** and **multi-product** customers should be nurtured to maintain loyalty.  
- **Low credit score** and **high complaint frequency** customers are high-risk groups that require priority attention.  
- Banks should implement tailored retention strategies for high-risk customers, including:
  - Personalized incentives  
  - Credit score improvement programs  
  - Fast complaint resolution mechanisms  

These actions can effectively reduce churn rates and improve customer loyalty.
