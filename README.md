# 🏦 Loan Risk Analytics — End-to-End Data Analysis Project

An end-to-end data analytics project focused on identifying and analyzing risk factors associated with offering loans to customers. This project walks through the entire data workflow — from raw data ingestion to data visualization — using MySQL, Python (Jupyter), and Power BI.

---

## 🎯 Objective

To assist financial institutions in evaluating customer risk before offering loans, by analyzing key behavioral, financial, and demographic data. The final deliverable includes a Power BI dashboard with actionable insights.

---

## 🧰 Tools & Technologies

| Tool         | Purpose                                 |
|--------------|------------------------------------------|
| **MySQL**    | Data storage, relational queries         |
| **Python**   | Data cleaning, preprocessing, and EDA    |
| **Jupyter**  | Interactive coding and visualization     |
| **Power BI** | Dashboard creation and business reporting |
| **Canva**    | Custom dashboard backgrounds              |

---

## 🔄 Project Workflow

1. **Data Ingestion**
   - Raw data loaded into MySQL (`Banking` database)
   - Structured across 4 relational tables

2. **Python + MySQL Connection**
   - Used `mysql-connector-python` to fetch data into Jupyter
   - Enabled handling of large datasets directly in Python

3. **Data Cleaning & EDA (Jupyter Notebook)**
   - Handled missing values, standardized columns, corrected types
   - Exploratory Data Analysis using `pandas`, `matplotlib`, `seaborn`
   - Identified patterns in credit card usage, loan history, income distribution, etc.

4. **Dashboard Creation (Power BI)**
   - 5-page dashboard built with Canva-designed backgrounds:
     - **Home Page**: Project intro + key KPIs
     - **Loan Analysis**: Loan trends, risks, and balances
     - **Deposit Analysis**: Customer savings & deposit behavior
     - **Summary**: Executive-level insights
     - **Ask**: Business recommendations and strategy

---

## 🗃️ Database Schema Overview (MySQL)

**Database:** `Banking`

### 🔹 Table: `Customer`
| Column Name                  | Type     | Description                        |
|-----------------------------|----------|------------------------------------|
| Client ID                   | Text     | Unique customer ID                 |
| Name                        | Text     | Customer full name                 |
| Age                         | Int      | Age of the customer                |
| Location ID                 | Int      | Geographical location              |
| Joined Bank                 | Text     | Account opening date               |
| Banking Contact             | Text     | Contact info                       |
| Nationality                 | Text     | Country of origin                  |
| Occupation                  | Text     | Employment category                |
| Fee Structure               | Text     | Type of banking fees               |
| Loyalty Classification      | Text     | Loyalty tier                       |
| Estimated Income            | Double   | Annual income                      |
| Superannuation Savings      | Double   | Retirement funds                   |
| Amount of Credit Cards      | Int      | Number of credit cards             |
| Credit Card Balance         | Double   | Total balance                      |
| Bank Loans                  | Double   | Loan amount                        |
| Bank Deposits               | Double   | Total deposits                     |
| Checking Accounts           | Double   | Checking balance                   |
| Saving Accounts             | Double   | Savings balance                    |
| Foreign Currency Account    | Double   | Foreign holdings                   |
| Business Lending            | Double   | Business-related credit            |
| Properties Owned            | Int      | Property count                     |
| Risk Weighting              | Int      | Calculated risk score              |
| BRId                        | Int      | FK: Banking Relationship           |
| GenderId                    | Int      | FK: Gender                         |
| IAId                        | Int      | FK: Investment Advisor             |

### 🔹 Lookup Tables
- **Gender**  
- **Investment Advisors**  
- **Banking Relationships**

---

## 📊 Dashboard Pages (Power BI)

1. **Home Page** — High-level overview and key performance indicators
2. **Loan Analysis** — Loan types, volumes, risk weights
3. **Deposit Analysis** — Savings, superannuation, and cash flows
4. **Summary** — Combined view of deposits, loans, and customer categories
5. **Ask** — Strategic insights and data-backed recommendations

Custom-designed layouts using **Canva** were used to improve report clarity and branding.

---

## 🔍 Key Insights

- Clear correlation between risk weighting and loan behavior
- Customers with higher income showed varied risk levels due to lifestyle and spending
- Loyalty classification played a key role in deposit behaviors
- Multiple credit cards and properties owned were tied to higher loan volumes

---

## 🙌 Author

**[Vivek Kumar]**  
Connect with me on [LinkedIn](https://www.linkedin.com/vivek-kumar-vt/)  
For queries or feedback, feel free to reach out!

---
