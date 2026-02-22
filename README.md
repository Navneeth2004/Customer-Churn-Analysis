# 📊 Banking Customer Churn Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Banking Customer Churn dataset to identify the key factors that influence customer attrition.  

Customer churn is a major challenge in the banking industry, as retaining existing customers is more cost-effective than acquiring new ones. This project analyzes customer demographics and financial attributes to uncover patterns, trends, and actionable business insights.

---

## 🎯 Problem Statement
Banks experience revenue loss when customers discontinue their services.  
The objective of this project is to analyze customer data and determine:

- Why customers leave the bank
- Which factors contribute most to churn
- How banks can improve customer retention

---

## 🎯 Project Objectives
- Understand dataset structure and variables
- Perform data wrangling and cleaning
- Conduct **Univariate, Bivariate, and Multivariate Analysis**
- Identify patterns, correlations, and anomalies
- Generate business insights
- Provide actionable recommendations

---

## 🛠️ Tools & Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 📂 Dataset Information
The dataset contains customer information from a banking institution.

### Key Features
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Churn Indicator)

Each row represents a unique bank customer.

---

## 🔍 Project Workflow

### 1️⃣ Dataset Loading
- Imported dataset using Pandas
- Displayed sample records
- Checked dataset dimensions and structure

### 2️⃣ Data Understanding
- Data type inspection
- Statistical summary
- Unique value analysis
- Data dictionary creation

### 3️⃣ Data Wrangling
- Removed irrelevant columns:
  - `RowNumber`
  - `CustomerId`
  - `Surname`
- Renamed columns for clarity
- Created new features:
  - **AgeGroup**
  - **BalanceZero**
  - **TenureGroup**

### 4️⃣ Data Cleaning
- Checked duplicate records
- Verified missing values
- Ensured data consistency

### 5️⃣ Exploratory Data Analysis
Performed:
- ✅ Univariate Analysis
- ✅ Bivariate Analysis
- ✅ Multivariate Analysis

### Visualizations Used
- Histograms
- Bar Charts
- Count Plots
- Box Plots
- Scatter Plots
- Violin Plots
- Pair Plot
- Correlation Heatmap

(20+ visualizations with insights)

---

## 📊 Key Insights
- Older customers have a higher probability of churn.
- Customers with higher balances are more likely to leave.
- Geography significantly affects churn behavior.
- Gender has minimal impact on churn.
- Customer tenure influences retention.

---

## ✅ Conclusion
The analysis shows that customer churn is mainly influenced by **age, balance, and geographic location**.  
Exploratory Data Analysis helps transform raw customer data into meaningful business intelligence for decision-making.

---

## 💡 Recommendations
- Provide loyalty rewards for long-term customers.
- Offer personalized services for older customers.
- Focus retention strategies on high-balance clients.
- Improve services in regions with higher churn rates.
- Monitor customers showing early churn indicators.

---

## 🚀 How to Run the Project

### 1. Clone Repository
```bash
git clone https://github.com/your-username/banking-customer-churn-eda.git
```

### 2. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn
```

### 3. Run Notebook
Open the notebook using Jupyter or upload it to Google Colab:
```bash
jupyter notebook Banking_Customer_Churn_EDA.ipynb
```

---

## 📁 Project Structure
```
Banking-Customer-Churn-EDA/
│
├── Banking_Customer_Churn_EDA.ipynb
├── Churn_Modelling.csv
├── README.md
└── images/ (optional)
```

---

## 👨‍💻 Author
**V Navneeth**  
B.Tech – Computer Science Engineering  
Cambridge Institute of Technology

---

## 📜 License
This project is created for educational and portfolio purposes.

---

