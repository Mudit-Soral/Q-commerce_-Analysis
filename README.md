# 📊 Q-Commerce Logistics & Revenue Analysis

An end-to-end data analytics project exploring delivery performance, customer behavior, and operational efficiency across 1 million Quick-Commerce orders.

## 🚀 Project Overview
This project transforms raw, noisy logistics data into actionable business intelligence. Using Python, I analyzed a dataset of ~947,000 orders to understand how platforms like Zepto, Blinkit, and Swiggy Instamart balance delivery speed with customer satisfaction and revenue growth.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy (Data Cleaning & Processing)
* **Visualization:** Matplotlib, Seaborn (Static Dashboards), Plotly (Interactive Charts)
* **Scaling:** Scikit-Learn (Min-Max Scaling for Efficiency Scoring)

## 📈 Key Insights & Findings
* **Efficiency Leader:** Zepto leads the market in operational efficiency, successfully maintaining high order volumes while keeping average delivery times lowest.
* **The Rating Paradox:** There is a near-zero correlation (**-0.001**) between delivery speed and partner ratings. This suggests that customers prioritize order accuracy over marginal speed gains.
* **Revenue vs. Volume:** Discounts significantly lift the Average Order Value (AOV) to **₹712.19**, but correlate with a lower total item count per order.
* **Consistency:** Logistics speed remains stable and consistent across the **12km operational zone**, showing high reliability in urban routing.

## 📂 Project Structure
1.  **Data Audit & Cleaning:** Handled missing values (Mode/Mean imputation) and removed outliers using percentile capping.
2.  **Exploratory Data Analysis (EDA):** Visualized distribution of order values, city volumes, and platform ratings.
3.  **Feature Engineering:** Developed a custom **Operational Efficiency Score** by normalizing Order Volume vs. Delivery Speed.
4.  **Executive Dashboard:** Created a consolidated KPI scorecard for high-level business review.

## 📝 Acknowledgments
Special thanks to the **DATA SCIENCE LOVERS** YouTube channel for providing the dataset and the foundational project guidance.
