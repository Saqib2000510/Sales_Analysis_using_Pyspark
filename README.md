# Sales_Analysis_using_Pyspark

## 🧠 Detailed Field Sales Analysis using PySpark & Databricks

**🔹Situation:**  
In the food retail industry, analyzing customer behavior and optimizing product offerings based on sales trends is crucial for increasing profitability and operational efficiency. The business lacked clarity on category-wise spending, regional sales trends, and top-selling items across various platforms like Swiggy and Zomato.

**🔹Task:**  
To build an end-to-end data engineering pipeline on Databricks using PySpark that extracts actionable insights from food delivery transactional data. The goal was to calculate key performance indicators (KPIs) to drive strategic business decisions.

**🔹Action:**  
- Built the entire data processing pipeline using **PySpark** in **Databricks Community Edition**.  
- Designed schemas and loaded datasets representing sales, customers, food categories, and platforms.
- Performed data cleaning, transformation, and aggregation to compute KPIs such as:
  - 💰 Total amount spent by each customer
  - 🍽️ Total amount spent per food category
  - 📅 Monthly, Quarterly, and Yearly Sales
  - 🥪 Top 5 ordered items and most frequently ordered items
  - 👥 Customer visit frequency
  - 🌍 Sales by Country
  - 📱 Sales by Order Source (e.g., Swiggy, Zomato)
- Used PySpark functions like `groupBy`, `agg`, `withColumn`, and `join` to perform transformations and analytics at scale.

**🔹Result:**  
- Identified **Sandwich** as the most ordered food item.  
- Discovered a **100% increase in yearly sales**, from ₹5K to ₹10K.  
- Found that the **UK** generated the highest overall sales.  
- Analyzed order source data and revealed that **Swiggy** was the dominant channel contributing to maximum revenue.

### 📂 Tech Stack

- **Language:** Python (PySpark)
- **Platform:** Databricks (Community Edition)
- **Data Processing:** Apache Spark
- **Data Source:** CSV files (customer, sales, menu data)
- **Tools:** Pandas (for light inspection), Databricks Notebook, Spark SQL

### 🚀 Key Takeaways

- Hands-on experience with distributed data processing using PySpark.
- Built KPIs that can directly inform business decisions.
- Applied real-world data analysis techniques to derive market trends.

### Dashboard Link: 
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3550675076766467/83530794266939/5457753784201326/latest.html
