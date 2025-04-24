# 📊 KFC Hyderabad Branch Sales Analysis – Python Notebook

## 🧾 Project Overview
This repository hosts an **interactive Jupyter Notebook** that dissects sales and customer behavior data for four KFC branches in Hyderabad (Ameerpet, Gachibowli, Kukatpally, Madhapur).

The notebook walks through:

| 🔢 Section | Purpose | Key Code Snippets |
|------------|---------|-------------------|
| **1 · Setup** | Import libraries & load dataset | `import pandas as pd`, `pd.read_excel()` |
| **2 · Quick Data Cleaning** | Parse dates, derive hour & weekday | `pd.to_datetime`, `.dt.hour`, `.dt.day_name()` |
| **3 · Branch-wise Revenue** | Horizontal bar chart of branch revenue | `groupby('Branch Location')` |
| **4 · Time-of-Day Trend** | Line plot of revenue by hour | `groupby('hour')` |
| **5 · Day-of-Week Trend** | Ordered bar chart of revenue by weekday | `reindex([...])` |
| **6 · Payment-Mode Share** | Pie chart of payment-method usage | `value_counts().plot(kind='pie')` |
| **7 · Customer Ratings** | Overall & branch-level averages | `df['Customer Rating'].mean()` |

Everything lives in **`KFC_Hyderabad_Analysis.ipynb`**.

---[Uploading pythonlib.html…]()


## 📂 Repository Structure
├── data/
│ └── KFC_Hyderabad_Customer_Behavior_1000_Rows.xlsx
├── KFC_Hyderabad_Analysis.ipynb
├── requirements.txt
└── README.md ← you are here


---
### 📍 Total Revenue by Branch
![image](https://github.com/user-attachments/assets/e67d88f2-9af3-4afb-9904-9b200e3740e9)

### ⏰ Revenue by Hour of Day
![image](https://github.com/user-attachments/assets/554981f5-fea4-4686-817b-dcfc8f0832aa)

### 🗓️ Revenue by Day of Week
![image](https://github.com/user-attachments/assets/134aa747-17cb-40d0-a65a-3cec230e0cd6)

### 💳 Payment Mode Share
![image](https://github.com/user-attachments/assets/16b05e29-e39b-4874-96a6-28d9ad7bdfa8)

### ⭐ Average Customer Rating by Branch
![image](https://github.com/user-attachments/assets/b12c9f97-20e0-4243-8525-3063d902056f)

### 🔄 Revenue vs Customer Rating
![image](https://github.com/user-attachments/assets/0b615e64-e63a-4702-a299-454bd3d57316)


## 🚀 Getting Started

## 🔍 Key Insights

- 📍 **Branch Performance**  
  - **Top Performer:** Gachibowli branch  
  - **Growth Opportunity:** Ameerpet branch  

- ⏰ **Peak Times**  
  - Weekend dinner hours show **35 % higher sales** than weekdays  

- 🍗 **Product Analysis**  
  - **Best‑seller:** Zinger Bucket (22 % of total sales)  
  - **Upsell Success:** Beverage combos increase average order value by **18 %**  
  - **Regional Preference:** Madhapur shows **40 % higher snack purchases** than other locations  

---

## 🧑‍💼 Customer Insights & Business Implications

| Metric | Finding | Business Implication |
|--------|---------|----------------------|
| ⭐ **Average Rating** | **4.2 / 5** (high satisfaction) | Maintain service quality |
| 💳 **Payment Mix** | 62 % digital (UPI / Cards) | Reduce cash‑handling overhead |
| ⏲ **Peak Hours** | 1 – 2 PM and 7 – 9 PM | Focus staff scheduling |
| 🔄 **Retention** | 20 % repeat customers | Launch loyalty program |

> 📊 **Sales‑Funnel Metrics diagram/code** available in the notebook.

---

## 🛠 Technology Stack

| Layer | Tools |
|-------|-------|
| **Core** | Python 3.11 |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib (ggplot style) |
| **Notebook** | Jupyter |
| **PDF Export** | nbconvert with `xelatex` |

---

## 🚀 Future Enhancements

- **Real‑time analytics**  
  - Integrate with **Azure SQL Database**  
  - Implement automated daily reporting

---

## 📈 Next Steps

1. **Predictive Analytics**  
   - Add demand‑forecasting models with **Prophet** or **statsmodels** to predict daily revenue and staffing needs.

2. **Interactive Dashboard**  
   - Publish key visuals as a **Streamlit** or **Dash** web app for operations managers.

3. **Automated Alerts**  
   - Use **schedule** + **SMTP / Slack API** to push notifications when KPIs (e.g., branch revenue, low ratings) cross thresholds.

4. **CI/CD for Notebooks**  
   - Integrate with **GitHub Actions** to run unit tests and regenerate charts on every data update.

---

## 🙌 Author

**Mohan Chandu Mamillapalli**  

- 📧 **Email:** chandumamillapalli425@gmail.com  
- 💼 **LinkedIn:** [linkedin.com/in/your‑link](https://www.linkedin.com/in/chandu425/)  
- 🐙 **GitHub:** [github.com/your‑username](https://github.com/chandu00096)


---

> *Feel free to fork, star, or open issues & pull requests. Contributions are welcome!*

