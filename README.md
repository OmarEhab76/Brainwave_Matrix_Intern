# 📊 Superstore Sales Analysis

## 🧠 Internship Project @ Brainwave Matrix Solutions

This project was part of my internship at **Brainwave Matrix Solutions**, where I explored the *Sample Superstore* dataset to uncover business insights and visual analytics for a retail giant. The goal was to understand **what drives profit**, **what products hurt the business**, and **which segments, regions, or categories should be focused on or avoided**.

---

## 📁 About the Dataset

**Context:**
With increasing market competition, a Superstore is looking to make data-informed decisions. This dataset helps explore patterns in product sales, regional performance, customer segments, and profitability. It also allows for predictive modeling (e.g., regression for sales/profit).

**Metadata Overview:**

| Column Name   | Description                                |
| ------------- | ------------------------------------------ |
| Row ID        | Unique row identifier                      |
| Order ID      | Order transaction ID                       |
| Order Date    | Date of purchase                           |
| Ship Date     | Date of shipment                           |
| Ship Mode     | Shipping method                            |
| Customer ID   | Unique customer identifier                 |
| Customer Name | Full name of customer                      |
| Segment       | Consumer/Corporate/Home Office             |
| Country       | Country of residence                       |
| City          | Customer city                              |
| State         | Customer state                             |
| Postal Code   | ZIP/postal code                            |
| Region        | Market region                              |
| Product ID    | Unique product ID                          |
| Category      | Product category (Furniture, Tech, Office) |
| Sub-Category  | Product sub-category                       |
| Product Name  | Name of the product                        |
| Sales         | Total sales amount                         |
| Quantity      | Units sold                                 |
| Discount      | Discount applied                           |
| Profit        | Profit or loss from the sale               |

---

## 📌 Key Insights

1. 📈 **Monthly Sales Boom Post-July 2017:**
   Sales volume increased significantly after July 2017. However, **profit did not increase proportionally**, suggesting discounts or cost issues.

2. 🧩 **Category-Level Insights:**

   * **Technology:** Phones are top-performing in terms of sales.
   * **Furniture:** Chairs outperform other items.
   * **Office Supplies:** Storage items are the best sellers.

3. 🗺️ **Regional Performance:**

   * **West** and **East** regions generate the **most sales**.
   * **South** and **Central** lag behind.

4. 🔥 **Top Loss-Making Products:**
   The attached heatmap highlights the **top 10 products generating the highest losses**, led by:

   * `Cubify CubeX 3D Printer Double Head Print`
   * `GBC DocuBind P400 Electric Binding System`
   * `Lexmark MX611dhe Monochrome Laser Printer`

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** for data wrangling
* **Plotly** for interactive and advanced visualizations
* **Matplotlib/Seaborn** for EDA (if needed)
* **Jupyter Notebook** for iterative analysis

---

## 📈 Future Improvements

* Build regression models to predict **Sales** and **Profit**
* Build dashboards using **Dash** or **Streamlit**
* Deep dive into **customer segmentation** or **market basket analysis**
