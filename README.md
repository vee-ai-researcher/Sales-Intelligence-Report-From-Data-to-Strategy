

# **Sales Intelligence Report: From Data to Strategy**

**Analyst:** Judith Chineze Onwuka
**Submission Date:** 09/05/2025

---

## **1. Introduction**

This report analyzes retail sales data to uncover key trends, evaluate product performance, understand customer behavior, and identify operational bottlenecks. The objective is to derive actionable insights to support data-driven decision-making in marketing, inventory control, and customer relationship management.

---

## **2. Dataset Description**

* **Source:** Classic Models Sales Dataset
* **Structure:** 25 columns, approximately 3000 rows
* **Key Variables:**

  * `ORDERDATE`, `SALES`, `PRODUCTLINE`, `CUSTOMERNAME`, `STATUS`, `QUANTITYORDERED`, `PRICEEACH`, `TERRITORY`
* **Time Span:** Includes sales data across various months and years with customer and geographic details.

---

## **3. Methodology**

### **Data Cleaning**

* Missing values in `POSTALCODE`, `STATE`, and `TERRITORY` were filled with placeholders like **"Unknown"**.
* `MONTH_ID` and `YEAR_ID` were merged into a single **datetime** column for time-series analysis.

### **Analysis Tools**

* **Pandas** for data processing
* **Matplotlib** and **Seaborn** for data visualization
* Visualizations generated to analyze trends, performance, and segmentation.

---

## **4. Dashboard Overview**

### Key Visuals and Purpose:

1. **Total Sales Over Time** *(Line Chart)*

   * Identifies overall sales trend and seasonality for forecasting.

2. **Sales by Product Line** *(Bar Chart)*

   * Highlights top-performing product categories.

3. **Top Customers by Sales** *(Horizontal Bar Chart)*

   * Reveals customers contributing highest revenue; supports upselling strategies.

4. **Monthly/Quarterly Sales Trends** *(Line Chart)*

   * Uncovers cyclical patterns useful for planning.

5. **Product Performance** *(Bar Chart)*

   * Compares individual product sales and quantity sold.

6. **Sales by Status** *(Pie Chart)*

   * Evaluates order fulfillment efficiency and highlights delays.

---

## **5. Key Findings & Insights**

* 🔷 **Quarter 4 Sales Peak**: Sales consistently spike in **Q4**, suggesting strong seasonal demand. Focused marketing and inventory planning before Q4 can increase profitability.

* 🔷 **Classic Cars Lead in Sales**: This product line outperforms others in both volume and revenue, indicating high customer preference.

* 🔷 **80/20 Rule Applies**: Top **10% of customers account for \~50% of total revenue**. A loyalty program and account-based marketing can help retain and grow these relationships.

* 🔷 **Off-Peak Months (Feb & Aug)**: These months show revenue dips, suggesting the need for targeted discounts or promotional strategies.

* 🔷 **Order Fulfillment Gaps**: A considerable number of orders are in “**On Hold**” or “**In Process**” status. Process optimization can improve cash flow and customer satisfaction.

* 🔷 **Underperforming High-MSRP Products**: These may require price restructuring or marketing revamp to improve turnover.

* 🔷 **Territory Data Gaps**: Missing territory values limit geographic analysis. Future data integrity efforts are essential for location-specific strategies.

---

## **6. Conclusion & Future Scope**

The analysis provides deep insights into customer buying behavior, product profitability, and operational challenges. Implementing targeted marketing, prioritizing high-value customers and products, and addressing fulfillment inefficiencies can significantly improve performance.

**Future Scope:**

* Develop **predictive models** for demand forecasting.
* Implement **customer segmentation** for personalized campaigns.
* Conduct **geographic sales analysis** once territory data is cleaned.

---

## **7. References**

* **Dataset**: Classic Models Sales Dataset (Kaggle/Other Sources)
* **Libraries Used**: Pandas, NumPy, Seaborn, Matplotlib
* **Style Guides**: Seaborn and Matplotlib documentation
