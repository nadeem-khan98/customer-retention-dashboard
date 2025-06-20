# 📊 Customer Retention Analysis Dashboard

A data analysis and visualization project aimed at understanding customer retention patterns, segment behavior, and revenue trends. The final outcome is a Power BI dashboard that enables actionable business insights.

---

## 🔍 Project Overview

Customer retention is crucial for long-term business growth. This project analyzes customer data to identify key factors influencing customer loyalty, spending behavior, and churn. The project includes data cleaning, exploratory analysis (EDA), and the creation of a Power BI dashboard.

---

## 📁 Dataset Summary

- **Source**: Synthetic customer transaction and demographic data  
- **Rows**: 100,000+  
- **Columns**: 15+  
- **Key Fields**:
  - `CustomerID`, `CustomerSegment`, `Tenure`, `TotalSpend`
  - `AverageBasketValue`, `LastPurchaseDate`, `City`, `Gender`
  - `CustomerType` (New/Returning)

---

## 🛠 Tools & Technologies

| Tool               | Usage                          |
|--------------------|-------------------------------|
| **Python**         | Data cleaning, EDA             |
| **Pandas**         | Data manipulation              |
| **Matplotlib/Seaborn** | Visualizations for EDA     |
| **Power BI**       | Interactive dashboard          |
| **Excel**          | Data format exploration        |
| **Jupyter Notebook** | Development environment     |

---

## 📈 Dashboard Structure (Power BI)

### 1️⃣ Customer Overview

- **KPI Cards**: Total Customers, Avg Basket Value, % Returning Customers, New Customers  
- **Charts**:
  - Pie Chart: Customer Segmentation  
  - Column Chart: Recency Segmentation  
  - Donut Chart: New vs Returning  
  - Bar Chart: Tenure Distribution  

### 2️⃣ Purchase & Revenue Analysis

- **KPI Cards**: Total Spend, Avg Spend per Customer, Revenue from Returning Customers, Max Purchase Value  
- **Charts**:
  - Stacked Column: Revenue by Segment Over Time  
  - Donut Chart: Revenue by Customer Type  
  - Bar Chart: Revenue by City/Country  
  - Line Chart: Monthly Revenue Trend  

### 3️⃣ Customer Loyalty & Tenure

- **KPI Cards**: Avg Tenure, Active Customers, Lost Customers  
- **Charts**:
  - Area Chart: Active vs Lost Customers Over Time  
  - Donut Chart: Loyalty Group Share  
  - 100% Stacked Chart: Segment by Tenure  
  - Bar Chart: Support Interactions by Segment  

---

## 📊 Exploratory Data Analysis (EDA)

Performed using Python:

- Customer count by segment, gender, and type  
- Age group and tenure distributions  
- Spending patterns: average basket size, total spend  
- Outlier detection in high spend customers  
- Recency and churn detection  

**Sample Visuals**:

- Boxplots for segment-wise basket value  
- Histograms for customer tenure  
- Bar charts for segment spending  

---

## ✅ Key Business Insights

- **Returning customers** contribute significantly more to revenue.  
- **Regular customers** have the highest average spend and retention.  
- **New customers** often churn within the first 60 days—highlighting onboarding importance.  
- **Tenure and engagement** strongly correlate with loyalty and spending.  

---

## 📌 Recommendations

- Introduce targeted loyalty programs for **new customers within 60 days**.  
- Focus **support efforts** on high-value segments (e.g., VIP and Regular).  
- Incentivize repeat purchases through **basket value–based promotions**.  
- Use tenure segmentation to customize offers by lifecycle stage.  

---

## 📂 Project Files

| File                          | Description                            |
|------------------------------|----------------------------------------|
| `Customer_Retention_EDA.ipynb` | EDA and data cleaning in Python       |
| `Dashboard.pbix`             | Power BI dashboard file                |
| `EDA.png`                    | Snapshot of EDA insights               |
| `Presentation.pptx`          | Project presentation                   |
| `README.md`                  | This project documentation             |
| `requirements.txt`           | Python libraries used                  |

---

## 💬 Author

**Nadeem Khan**  
Data Analyst | Python • Power BI  
📧 Email: khan.datawave@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/nadeem-khan98)

---

## 📥 How to Use

1. Clone/download the repository  
2. Open `.ipynb` in Jupyter to explore EDA  
3. Open `.pbix` in Power BI Desktop to interact with the dashboard  
4. Use the presentation slides to explain your approach in interviews or reviews  

---

## 📃 License

This project is for educational and portfolio purposes only.

# customer-retention-dashboard
