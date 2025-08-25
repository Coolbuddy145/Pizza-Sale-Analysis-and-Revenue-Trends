# 📊 Pizza Sales Analysis – Revenue & Trends

## 🔎 Project Overview

The objective of this project is to analyze the Sales and Revenue of Pizza sales by building an interactive dashboard.
The dashboard provides insights into customer preferences, revenue drivers, and product performance, helping stakeholders make data-driven business decisions.

The analysis addresses key questions:

* Total Revenue Generated: How much revenue was earned over the year?

* Daily Sales Trend: What does the day-to-day sales pattern reveal about customer behavior?

* Monthly Sales Trend: Which months performed well, and where did sales dip?

* Average Order Value (AOV): On average, how much revenue is generated per order?

* Average Pizzas per Order: How many pizzas does a customer typically order in one transaction?

* Top 5 Pizzas by Revenue: Which pizzas contribute the most to overall revenue?
  
---

## ⚙️ Dataset Information

* pizza_id - Unique identifier for each Pizza	
* order_id - Unique identifier for each order	
* quantity - No of Pizzas Sold
* order_date - Date on which Pizza ordered
* order_time - Time at which Pizza Ordered
* unit_price -  Price of each quantity
* total_price - Total Price of order
* pizza_size - Size of Pizza (Regular, Medium, Large)
* pizza_category -  Category of Pizza (Supreme, Classic, Chicken, Veggie)
* pizza_ingredients - Ingredients Used
* pizza_name -  Name of the Pizza

* Dropped `emp_title`, `id`, `member_id`, `total_acc` (low value).
* Converted `term` from object to integer.
* Kept outliers as they reflect real-world cases (e.g., high income, large loans).

---

## 📈 Key Insights

* **Loan Purpose:** Most loans for **debt consolidation & credit card repayment**; medical, education, and housing loans underrepresented. → Opportunity for targeted products.
* **Home Ownership:** Majority are **renters/mortgage holders**; few own homes outright. → Tailor products (home renovation for renters, investment/business loans for owners).
* **Tenure:** Only **36 & 60 month loans**, with 36 months dominating. → Preference for shorter-term, lower-risk lending.
* **Experience:** Borrowers with **10+ years work experience** receive highest loan amounts, seen as lower risk.
* **Loan Amount vs Rate:** No strong correlation; smaller loans cluster around 7–15% interest.
* **Grade & Rate:** Very strong correlation (0.94). Lower grades → higher interest rates.
* **Grade & Default Risk:** Defaults increase from A→G; Grades F & G are high-risk. → Grading system effectively flags risk.
* **Geography:** California, New York, Texas, Florida lead in applications & funding.
* **Time Trends:** Loan applications, amounts received & funded nearly **doubled by year-end**, signaling growth & profitability.
* **DTI:** Bank funds loans mainly for **DTI <30%**, avoiding high-risk borrowers (>35%).

---

## 📌 Business Value

* Confirms **grading and DTI** effectively manage risk.
* Identifies **growth opportunities** in underrepresented loan purposes & renter/mortgage-holder segments.
* Highlights **profitability trend** with rising loan demand.
* Suggests tighter monitoring of **Grades F & G**.

---
