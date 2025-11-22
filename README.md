# 🧾 Ferns-and-Petals-Sales-Data-Analysis
 
## 📌 Overview  
This is my **first data analysis project** using **Microsoft Excel**.  
The project demonstrates how to clean, organize, and visualize sales data by creating an **interactive dashboard**.  

The main goal is to analyze sales performance and provide insights in a clear, visual way.  

---

## 📊 Project Details  

- **Tools Used:** Microsoft Excel  
- **Dataset:** Sample sales data (products, customers, orders, dates)  
- **Techniques Applied:**  
  - Data cleaning & formatting  
  - Pivot tables & charts  
  - Dashboard design  

---

## 📈 Dashboard Preview  

<img width="1058" height="368" alt="Dashboard" src="https://github.com/user-attachments/assets/100fea05-375c-433e-b21e-d9924ea6a14c" />


----

## 📈 Resuls Preview & Pivot Tables
----------------------------------
| Sum of revenue | $3,520,984.00 |
|----------------|---------------|
----------------------------------
| Average of revenue | $3,520.98 |
|--------------------|-----------|
----------------------------------
| Average of delivery time | 5.53 |
|--------------------------|------|
----------------------------------
| Order Quantity vs. DeliveryTime | 0.0039 |
|---------------------------------|--------|
- Using Correlation Function
This means that there is no strong relationship between the order quantiy and the delivery time.
----------------------------------
| Orders by Genders | Sum of revenue |
|-------------------|----------------|
| Female            | 1,730,761.00   |
| Male              | 1,790,223.00   |
| Grand Total       | 3,520,984.00   |
----------------------------------
| Month       | Total of revenue |
|-------------|------------------|
| January     | 95,468.00        |
| February    | 704,509.00       |
| March       | 511,823.00       |
| April       | 140,393.00       |
| May         | 150,346.00       |
| June        | 157,913.00       |
| July        | 135,826.00       |
| August      | 737,389.00       |
| September   | 136,938.00       |
| October     | 151,619.00       |
| November    | 449,169.00       |
| December    | 149,591.00       |
| Grand Total | 3,520,984.00     |
----------------------------------
| Products Name | Total of revenue |
|---------------|------------------|
| Deserunt Box  | 97,665.00        |
| Dolores Gift  | 106,624.00       |
| Harum Pack    | 101,556.00       |
| Magnam Set    | 121,905.00       |
| Quia Gift     | 114,476.00       |
| Grand Total   | 542,226.00       |
----------------------------------
| Products Category | Sum of revenue |
|-------------------|----------------|
| Cake              | 329,862.00     |
| Colors            | 1,005,645.00   |
| Mugs              | 201,151.00     |
| Plants            | 212,281.00     |
| Raksha Bandhan    | 297,372.00     |
| Soft Toys         | 740,831.00     |
| Sweets            | 733,842.00     |
| Grand Total       | 3,520,984.00   |
----------------------------------
| Top Cities     | Count of Order_ID |
|----------------|-------------------|
| Alwar          | 7                 |
| Bareilly       | 9                 |
| Bhilai         | 8                 |
| Bulandshahr    | 7                 |
| Darbhanga      | 7                 |
| Ghaziabad      | 9                 |
| Hazaribagh     | 7                 |
| Khammam        | 7                 |
| Lucknow        | 7                 |
| Muzaffarnagar  | 7                 |
| Grand Total    | 75                |
----------------------------------
| Occasions       | Total of revenue |
|-----------------|------------------|
| All Occasions   | 586,176.00       |
| Anniversary     | 674,634.00       |
| Birthday        | 408,194.00       |
| Diwali          | 313,783.00       |
| Holi            | 574,682.00       |
| Raksha Bandhan  | 631,585.00       |
| Valentine's Day | 331,930.00       |
| Grand Total     | 3,520,984.00     |
----------------------------------
| Top Hours of Orders | Total of revenue |
|---------------------|------------------|
| 5                   | 156,198.00       |
| 6                   | 177,211.00       |
| 12                  | 162,394.00       |
| 15                  | 163,586.00       |
| 17                  | 155,373.00       |
| 18                  | 173,118.00       |
| 19                  | 185,771.00       |
| 20                  | 186,426.00       |
| 21                  | 155,466.00       |
| 23                  | 168,511.00       |
| Grand Total         | 1,684,054.00     |
----------------------------------
| Row Labels       | Total of revenue |
|------------------|------------------|
| Akarsh Ramesh    | 50,313.00        |
| Anahita Shankar  | 49,100.00        |
| Aradhya Batta    | 50,856.00        |
| Divit Mahajan    | 61,294.00        |
| Jhanvi Chowdhury | 59,666.00        |
| Mannat Anand     | 49,494.00        |
| Ranbir Loyal     | 53,082.00        |
| Samaira Ganesh   | 75,029.00        |
| Seher Mann       | 70,409.00        |
| Veer Ray         | 50,151.00        |
| Grand Total      | 569,394.00       |
----------------------------------
---
## 🔑 Business Questions & Answers


1- Total Revenue → SUM(revenue) → $3,520,984


2- Average Order and Delivery Time → AVERAGE(delivery_date - order_date) → 5.5 days


3- Monthly Sales Performance → Pivot by month → Aug then Feb highest, Jan lowest


4- Top Products by Revenue → Pivot SUM(revenue) by product → Colors, Soft Toys, Sweets


5- Customer Spending Analysis → AVERAGE(revenue per customer) → $3,520


6- Sales Performance by Top Product → Pivot filtered by product → Compare revenues


7- Top 10 Cities by Orders → Sort COUNT(order_id) → Ghaziabad, Bareill


8- Order Quantity vs. Delivery Time → Use correlation → 0.0039 (no strong relationship)


9- Revenue Comparison Between Occasions → Pivot by occasion → Anniversary & Raksha Bandhan in the top


10- Product Popularity by Occasion (Slicer) → Use slicer → Interactive filtering


11- Top Hours of Orders → Extract hour → Peaks at 18–21 & 5–6


12- Orders by Gender in General → Pivot by gender → Male 51%, Female 49%


13- Top 10 Buyers → Rank customers by SUM(revenue) → Highest spenders


14- Order Date Timeline → Line chart by order date → Shows sales trend



## 🚀 Key Insights  

- Top-performing products and categories  
- Seasonal trends in sales  
- Customer behavior patterns  
- Overall revenue distribution  

---

## 💡 Recommendations

Launch seasonal campaigns & flash sales for low-sales months (e.g., Jan) and top occasions (Feb, Aug).

Promote top products with bundles, upsells, and gift sets to increase revenue.

Offer tiered discounts or free shipping to boost average order value.

Reduce delivery time via local warehouses, 3PL partners, or express shipping for extra fee.

Schedule marketing pushes during peak hours (18–21 & 5–6) and personalize offers.

Implement loyalty programs and track high-value customers for retention.



## 🗂 Files in This Repository  

- `Results & Dashboard.xlsx` → The main Excel file containing data & dashboard
- `Original Folder` → The main Excel file containing data before cleaning contains ( `customers.xlsx`, `orders.xlsx`, `products.xlsx` )
- `Recommendations for Sales, Profitability & Performance.pdf` → For Recommendations Details
- `README.md` → This file  
