# 📊 Retail Sales Analysis Project  

An interactive Power BI dashboard providing deep insights into **retail performance across regions, products, and years**. This project helps decision-makers track sales trends, profitability, and product performance to drive growth and optimize strategy.  

---

## 📁 Project Description  

This project focuses on **sales performance analysis and visualization** using retail transaction data. The dashboard highlights:  

- Revenue growth trends year-over-year  
- Average units sold per product  
- Regional revenue and profit comparison  
- Product-level contribution to total revenue  
- Cost vs. price analysis for profitability tracking  
- Total revenue insights for the selected date range  

---

## 📁 Project Structure  

```
retail_sales_analysis
├── Retail_Sales_data_dirty.csv    # Processed dataset
├── retail_dashboard.pbix          # Power BI dashboard file
└── README.md                      # Project documentation
```

---

## 🔧 Data Preparation Steps  

### 1. Remove Unnecessary Columns  
- The column **`sales_rep`** was identified as non-essential to this analysis and removed to streamline the dataset.  

### 2. Handle Null Values  
- Rows containing **null or missing values** were dropped to maintain data integrity and avoid errors in the analysis.  

### 3. Remove Duplicate Entries  
- Duplicate records were identified and eliminated to ensure the accuracy of aggregated metrics and visuals.  

### 4. Data Type Conversions  
- **Date Columns** (e.g., `order_date`) → Converted to *Date/Time*.  
- **Numeric Columns** (`revenue`, `cost`, `profit`) → Converted to *Decimal Number*.  
- **Categorical Columns** (`product`, `region`) → Set as *Text/Categorical* for filtering and slicing.  

### 5. Feature Engineering – New Calculated Columns  
- Created a new column **Profit Margin** using the formula:  
  ``` 
  Profit Margin = Profit / Revenue 
  ```

---

## 🔍 Key Metrics and Insights  

### 💰 Total Revenue  
- Achieved **25.92M** across the selected date range.  

### 📈 Revenue Trend  
- Revenue increased from **12.8M in 2023** to **13.2M in 2024**.  

### 📦 Average Units Sold  
- On average, **10.22 units** sold per order.  

### 🌍 Revenue & Profit by Region  
- Top-performing regions: **Europe** and **South America** with strong profit margins.  

### 🛒 Revenue Contribution by Product  
- Leading products: **Router (17.4%)** and **Monitor (16.6%)** of total revenue.  

### ⚖️ Price vs. Cost Analysis  
- Clear visibility into profit margins across each product category.  

---

## 🛠️ Tools & Technologies  

- **Power BI** – Dashboard development and visualization  
- **Microsoft Excel** – Initial data cleaning and transformation  
- **Retail Dataset** – Sales transaction records across multiple regions and products  

---

## ✅ Project Objectives  

- Monitor and analyze total revenue growth.  
- Identify top-performing regions and products.  
- Evaluate profit margins across different categories.  
- Provide actionable insights for strategic retail decisions.  

---

## 💼 Use Cases  

- **Retail Managers**: Track performance and adjust sales strategy.  
- **Business Analysts**: Perform profitability and trend analysis.  
- **Executives**: Get a high-level overview of revenue growth and product contribution.  
- **Data Enthusiasts**: Practice real-world business intelligence visualization.  

---

## 🔮 Future Enhancements  

- Incorporate **forecasting models** for future sales predictions.  
- Add **customer segmentation analysis**.  
- Integrate with **real-time sales data** for live updates.  
- Deploy dashboard using **Power BI Service** for organization-wide access.  

---

## 🙋‍♂️ Author  

**[Shiv Kumar**  

## 📬 Contact  

For feedback, queries, or collaborations, feel free to reach out!  

⚠️ Note: This project is for educational and analytical purposes only.  
