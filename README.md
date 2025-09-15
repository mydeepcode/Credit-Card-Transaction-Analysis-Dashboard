# 💳 Credit Card Transaction Analysis Dashboard (Power BI Project)

📌 **Project Purpose**
This dashboard analyzes **credit card transactions** to provide insights into **spending patterns, transaction volumes, and category-wise expenses**. It helps financial institutions and individuals track **where money is being spent, monthly spending trends, and customer behavior**.

---

## 🛠️ Tech Stack

* Power BI Desktop
* Power Query for ETL (Extract, Transform, Load)
* DAX (Data Analysis Expressions)
* Excel/CSV dataset of transactions

---

## 📊 Data Source

* **Format:** .csv / .xlsx
* **Rows:** \~1M transactions
* **Columns:** Transaction ID, Customer ID, Amount, Category, Date, Card Details
* **Source:** Simulated banking/credit card transaction dataset

---

## ✨ Features & Highlights

### 🧩 6.1.1 Business Problem

Banks and credit card providers need to **track spending patterns, detect overspending, and identify customer preferences**. Without proper monitoring, it is difficult to:

* Detect high-spending months
* Understand customer purchase categories
* Optimize marketing strategies based on user behavior

---

### 🎯 6.1.2 Dashboard Goals

* Show **Total Spend, Total Transactions, Average Transaction Value**
* Analyze **spend distribution by category** (Shopping, Personal Care, Home, Entertainment, etc.)
* Track **spend trend by month**
* Provide **customer-level insights** (using slicers & filters)
* Support **fraud detection & financial analysis**

---

### 📊 6.1.3 Key Visuals

* **KPI Cards**:

  * Total Spend: **\$73.69M**
  * Total Transactions: **1M**
  * Average Transaction Value: **\$70.28**

* **Pie/Donut Chart (Spend by Category):**

  * Shop Online: **\$28.12M (38.16%)**
  * Personal Care: **\$17.68M (24%)**
  * Home: **\$14.83M (20.13%)**
  * Entertainment: **\$13.05M (17.71%)**

* **Bar Chart (Spend by Month):**

  * Spending spikes in **December (\~\$10M)**
  * Consistent spending across other months

* **Credit Card Holder Detail Section**:

  * Displays **card details & name (e.g., Aaron Murray)**

* **Sidebar Navigation Panel**:

  * Dashboard | Payments | Statistics | Cards | Settings | Help

---

### 💼 6.1.4 Business Impact & Insights

* 📈 **Online Shopping** is the largest spend category (**\$28.12M**), suggesting customers prefer digital purchases.
* 🎉 Spending peaks in **December**, indicating **holiday season impact** (Christmas/New Year).
* 💳 High spend on **Personal Care (\$17.68M)** shows demand for lifestyle/health products.
* 🏡 Home & Entertainment categories combined make up **\$27.88M**, showing strong household + leisure spending.
* ✅ Helps banks in **customer segmentation, targeted offers, fraud detection, and revenue optimization**.

---

🖼️**Here is the link:**
[View Full Dashboard Image](https://github.com/mydeepcode/Credit-Card-Transaction-Analysis-Dashboard/blob/main/Credit%20Card%20Transaction%20Analysis%20Dashboard.png)
---

## 📎 Extras

* Slicer for **Customer ID / Card ID**
* Drill-through for **detailed transaction history**
* Can be extended to detect **fraudulent transaction spikes**
