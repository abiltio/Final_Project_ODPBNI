# 🏦 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict customer churn for a financial institution using various machine learning models. By analyzing key customer attributes, the model identifies customers at risk of leaving and helps implement targeted retention strategies.

## 📂 Dataset Information
- **Source**: A dataset containing customer demographics, account details, and churn status.
- **Size**: 10,000 records
- **Key Features**:
  - `CreditScore` - Customer's credit score.
  - `Geography` - Customer’s country.
  - `Gender` - Male or Female.
  - `Age` - Customer’s age.
  - `Tenure` - Number of years as a customer.
  - `Balance` - Account balance.
  - `NumOfProducts` - Number of products held.
  - `HasCrCard` - Whether the customer has a credit card.
  - `IsActiveMember` - Whether the customer is active.
  - `EstimatedSalary` - Estimated annual salary.
  - `Exited` - Churn status (1 = churned, 0 = not churned).

## 🚀 Machine Learning Models Used
The following machine learning models were implemented and compared:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest (Best Performing Model)**
- **XGBoost**

## 📊 Model Evaluation & Results
The **Random Forest Classifier** provided the best balance between precision and recall, making it the preferred model.

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|------------|--------|----------|
| Logistic Regression | 81.7%    | 59.3%      | 21.8%  | 31.9%    |
| Decision Tree      | 76.2%    | 43.4%      | 70.2%  | 53.7%    |
| **Random Forest**  | **85.7%** | **49.3%**  | **57.6%** | **57.6%** |
| XGBoost           | 85.9%    | 44.2%      | 64.1%  | 64.2%    |

## 📈 Key Findings
1. **Age & Credit Score are the strongest predictors of churn.**
2. **Active members are less likely to churn.**
3. **Customers with fewer products tend to leave.**
4. **Balance has a weak but notable impact on churn probability.**

## 🎯 Business Recommendations
### ✅ **1️⃣ Strategy for Low-Risk Customers (61.3%)**
✔ Maintain engagement with loyalty perks and referral programs.

### ✅ **2️⃣ Strategy for Medium-Risk Customers (22.4%)**
✔ Proactive support, targeted offers, and personalized communication.

### ✅ **3️⃣ Strategy for High-Risk Customers (16.3%)**
✔ Immediate intervention with retention offers and better support.


## 🏗️ Future Improvements
- Experiment with deep learning models (e.g., Neural Networks).
- Implement real-time churn prediction API.
- Optimize hyperparameters further for better precision and recall.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Pull requests are welcome! If you have suggestions, open an issue or submit a PR.

## 📬 Contact
For questions, feel free to reach out:
- 📧 Email: abiltio1604@gmail.com
- 🔗 LinkedIn: https://www.linkedin.com/in/abiltiokenda/

