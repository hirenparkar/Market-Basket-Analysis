# 🛒 Market Basket Analysis Dashboard

This project presents a **Market Basket Analysis** conducted using **Power BI** to uncover product purchase patterns and insights from transaction data. The analysis helps identify product associations, enabling businesses to optimize product placements, marketing strategies, and cross-selling opportunities.

![image](https://github.com/user-attachments/assets/1c966015-21e3-445b-9d3a-ff8c88686887)


---

## 📊 Dashboard Overview

The Power BI dashboard is designed with interactive visualizations to deliver comprehensive insights into customer purchasing behavior.

### Key Metrics
- **Total Transactions:** 7,835  
- **Product Count:** 170  

### Visual Components
1. **Basket Analysis Network**  
   - A network graph visualizing the relationships between frequently purchased products.  
   - Node size indicates the strength of product association (higher frequency = larger node).  
   - Example: Strong association between **Yogurt**, **Root Vegetables**, and **Whipped/Sour Cream**.

2. **Basket Analysis Map**  
   - Scatter plot showing the relationship between **Lift** and **Support** for product pairs.  
   - Helps identify product combinations with high purchase frequency and strong correlation.  
   - Example: **Root Vegetables** and **Other Vegetables** show high support and lift.

3. **Basket Analysis Details**  
   - A detailed table showcasing the most frequent product combinations with:  
     - **Support**: Frequency of product pair occurrence in all transactions.  
     - **Confidence**: Likelihood of purchasing the second product when the first is bought.  
     - **Lift**: Strength of association between two products.  
   - Example:  
     - **Domestic Eggs → Butter** has **0.91% Support** and **14.20% Confidence**.  
     - **Frozen Vegetables → Chicken** has **0.65% Support** and **13.67% Confidence**.

---

## ⚙️ How It Works

1. **Data Collection:**  
   - Transactional data comprising 7,835 purchases and 170 unique products was used.

2. **Association Rule Mining:**  
   - Market Basket Analysis was performed to find associations between items.  
   - Metrics used: **Support**, **Confidence**, and **Lift**.

3. **Visualization in Power BI:**  
   - Interactive visualizations were created to explore item relationships and purchasing patterns.

---

## 🚀 Features

- **Interactive Network Graph:** Quickly identify key product relationships.  
- **Lift vs. Support Map:** Understand product combinations with strong buying patterns.  
- **Detailed Association Table:** Dive deep into product pair statistics for actionable insights.

---

## 🛠️ Tools & Technologies

- **Power BI** for data visualization and analysis  
- **Market Basket Analysis (Apriori Algorithm)** for association rule mining  
- **DAX (Data Analysis Expressions)** for data manipulation

---

## 📈 Business Insights

- **Cross-Selling Opportunities:**  
  Products like **Yogurt** and **Whipped/Sour Cream** are often bought together, suggesting bundle promotions.

- **Product Placement:**  
  High-lift pairs such as **Frozen Vegetables** and **Chicken** can be co-located to boost sales.

- **Inventory Planning:**  
  Popular combinations help forecast product demand more accurately.
