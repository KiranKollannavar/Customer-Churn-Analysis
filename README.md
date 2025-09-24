# Customer Churn Analysis

## 📋 Project Overview
This project investigates **customer churn patterns** to help businesses understand the key factors driving customer attrition.  
The analysis focuses on **contract types, payment methods, tenure, internet service type, and demographics** to identify actionable strategies that can improve customer retention.

---

## 🎯 Objective
Identify the most significant factors influencing customer churn and recommend data-driven actions to reduce churn and increase long-term customer loyalty.

---

## 🗂️ Dataset
- **Source**: https://www.kaggle.com/datasets/blastchar/telco-customer-churn 
- **Size**: (e.g., ~7,000 records, 20+ features)  
- **Key Features**: Customer demographics, account details, payment method, contract type, internet service type, and churn label.

---

## 🔑 Key Insights

### 1️⃣ Contract Type
- **Month-to-Month Contracts:** Highest churn rate at **42%**.  
- **One-Year Contracts:** Moderate churn rate at **11%**.  
- **Two-Year Contracts:** Lowest churn rate at **3%**.  
**Implication:** Incentivizing customers to choose long-term contracts significantly improves retention.

### 2️⃣ Payment Methods
- **Electronic Checks:** Churn rate of **45%** (highest).  
- **Other Methods (credit card, bank transfer, mailed check):** Churn rates average **15–18%**.  
**Implication:** Customers paying via electronic checks may have convenience or trust concerns.  

### 3️⃣ Tenure
- **< 1 Year:** Churn rate of **50%**.  
- **1–3 Years:** Drops to **35%**.  
- **> 3 Years:** Falls further to **15%**.  
**Implication:** Early customer engagement (first year) is critical.

### 4️⃣ Internet Service Type
- **Fiber Optic Users:** Churn rate of **30%**.  
- **DSL Users:** Churn rate of **20%**.  
**Implication:** Potential dissatisfaction with fiber optic service quality or competitive offers.

### 5️⃣ Senior Citizens
- **Age 65+:** Churn rate of **41%**.  
- **Under 65:** Churn rate of **26%**.  
**Implication:** Seniors may need targeted support or personalized retention programs.

---

## 📊 Visualizations
The notebook includes:
- **Bar Charts & Line Graphs** showing churn rates across payment methods, contract types, and tenure brackets.
- **Percentage Distribution** of churn for easy comparison of factors.

---

## 💡 Recommendations
Based on the analysis:
1. **Promote Long-Term Contracts**  
   Offer discounts or perks for 1–2 year plans to lower churn from 42% to ~10%.
2. **Encourage Stable Payment Methods**  
   Campaigns to migrate users from electronic checks to credit cards/bank transfers can reduce churn by up to 30 percentage points.
3. **Strengthen Early Engagement**  
   Loyalty programs or onboarding support during the first year can cut churn risk (currently 50%) dramatically.
4. **Improve Fiber Optic Experience**  
   Investigate service quality issues and enhance reliability to retain fiber optic customers.
5. **Senior-Centric Programs**  
   Provide personalized support, senior discounts, or dedicated customer service for the 65+ demographic.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Navigate to the project directory:
   ```bash
   cd <repo-name>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the notebook:
   ```bash
   jupyter notebook Customer_Churn_Analysis.ipynb
   ```

---

## 📈 Business Impact
Implementing these recommendations can **reduce churn by 20–30%**, directly improving recurring revenue and customer lifetime value.

