# 📉 Customer Churn Prediction using Machine Learning

This project is focused on predicting customer churn using a dataset from a telecommunications company. The goal is to identify customers who are likely to stop using the service, and understand the business factors behind churn, enabling proactive retention strategies.


## 🧠 Objective

The main objective of this project is to:

- Analyze customer data to discover patterns and churn drivers
- Build machine learning models to **predict churn**
- Compare models to select the best performing one
- Translate insights into **actionable business recommendations**


## 📊 Dataset

- **Source**: Telco Customer Churn Dataset (from IBM Sample Datasets or Kaggle)
- **Rows**: 7043 customers
- **Columns**: 21 (features include customer demographics, services, payment info, etc.)
- **Target**: `Churn` (Yes/No)



## 🔍 Exploratory Data Analysis (EDA)

We explored the data using Seaborn and Matplotlib. Key visualizations include:

- ✅ Pie chart showing **overall churn rate**
- ✅ Histograms for **tenure** and **monthly charges** by churn
- ✅ Countplots for **contract type** and **payment method** vs churn
- ✅ Correlation heatmaps for numeric features

These helped us form business insights such as:
- Customers with short tenure churn more
- Month-to-month contracts are associated with higher churn
- Electronic check users churn more than credit card users
- Higher charges lead to higher churn risk



## 🤖 Machine Learning Models

We trained and evaluated the following models:

| Model                 | Accuracy |
|----------------------|----------|
| Logistic Regression  | ~80%     |
| Random Forest        | ~82% ✅ Best |
| Support Vector Machine (SVM) | ~78% |
| K-Nearest Neighbors  | ~75%     |
| Naive Bayes          | ~72%     |

- We used **Label Encoding**, **Feature Scaling**, and **Train-Test Split**.
- Models were evaluated using **Accuracy**, **Confusion Matrix**, and **Classification Report**.
- Best-performing model: **Random Forest Classifier**



## 📈 Visualizations

All visualizations used for EDA and model comparison are saved in the `visuals/` folder. These include:

- Churn Distribution Pie Chart
- Tenure Distribution by Churn
- Monthly Charges KDE by Churn
- Contract Type vs Churn
- Model Accuracy Bar Plot

---

## 🧠 Business Insights

This project doesn't just build a predictive model — it **translates data into business value**:

- **~27% of customers churn** — a serious revenue leakage
- Customers with **month-to-month contracts churn at 42%**, vs just 11% on long-term contracts
- **Short-tenure users (<12 months)** are most likely to leave — onboarding needs improvement
- **Electronic check** as a payment method is a major churn signal
- Our model can help businesses **predict churners in advance** and run targeted retention campaigns



## 💼 Business Recommendations

| Strategy | Explanation |
|----------|-------------|
| 🎯 Target short-tenure users | Offer onboarding perks or welcome incentives |
| 📄 Encourage long-term contracts | Provide discounts to switch from month-to-month |
| 💳 Avoid churn-prone payment methods | Encourage auto-pay or credit card users |
| 📢 Use model predictions | Export churn scores weekly to customer support & marketing |


## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy** (data cleaning & processing)
- **Seaborn, Matplotlib** (visualizations)
- **Scikit-learn** (modeling)
- **Jupyter Notebook**



## 📌 Future Improvements

- Use **SMOTE** for class imbalance
- Deploy the model with a **Streamlit app** for business users
- Incorporate **customer sentiment or feedback** as additional features
- Track model performance over time with real churn data

---
## 🙋‍♀️ About Me

I'm a third-year Computer Applications student with a passion for data science. This project reflects my ability to combine technical machine learning skills with real-world business thinking. Looking for roles in **Data Analysis** or **Data Science**.

📫 Reach me on [LinkedIn](www.linkedin.com/in/tanvi-sharma25)  
📂 Portfolio: [My Portfolio ->](https://tanvirohitsharma.my.canva.site/portfolio)

---

## ⭐ Star This Repo

If you found this project useful, please give it a ⭐ on GitHub. It helps me grow!


