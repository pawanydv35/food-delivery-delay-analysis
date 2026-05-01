---

# 🍔 Food Delivery Delay & Cancellation Analysis

## 📌 Project Overview

Online food delivery platforms often face challenges such as **delivery delays** and **order cancellations**, which negatively impact customer satisfaction and business performance.

This project focuses on analyzing food delivery data to identify the **key factors contributing to delays and cancellations**, and to provide **data-driven insights** that can help improve delivery efficiency.

---

## 🎯 Objectives

* Analyze patterns in **delivery delays**
* Identify factors affecting delivery time:

  * Distance
  * Traffic conditions
  * Restaurant preparation time
  * Time of order
* Examine **order cancellation trends**
* Provide **actionable business insights** to reduce delays and cancellations

---

## 📊 Dataset

The dataset contains information related to food delivery operations, including:

* Order details (time, status)
* Delivery time (expected vs actual)
* Distance between restaurant and customer
* Traffic conditions
* Restaurant preparation time

---

## 🧹 Data Processing

* Handled missing and inconsistent values
* Converted time-based columns into proper formats
* Created new features such as:

  * **Delivery Delay** = Actual Time – Expected Time
  * Peak hours indicator
  * Weekend indicator

---

## 📈 Exploratory Data Analysis (EDA)

Key analyses performed:

* Delivery delay trends across different time periods
* Impact of **traffic** on delivery time
* Relationship between **distance and delay**
* Identification of **high-delay restaurants/areas**
* Analysis of **cancellation patterns**

---

## 📊 Dashboard

An interactive dashboard was created using **Power BI** to visualize:

* Average delivery time
* Percentage of delayed orders
* Cancellation rate
* Delay trends by time, traffic, and distance

---

## 🔍 Key Insights

* High traffic conditions significantly increase delivery delays
* Longer delivery distances are associated with higher delay probability
* Peak hours show increased delay and cancellation rates
* Certain restaurants consistently have longer preparation times

---

## 💡 Recommendations

* Optimize delivery partner allocation during peak hours
* Introduce buffer time in high-traffic conditions
* Monitor and improve performance of slow restaurants
* Use data insights for better operational planning

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy)
* **SQL** (Data Cleaning & Querying)
* **Power BI** (Dashboard & Visualization)
* **Excel** (Initial Exploration)

---

## 📁 Project Structure

```
food-delivery-delay-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│
├──  sql/
│    ├── queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── reports/
│   └── final_report.pdf
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:

   ```
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run the analysis files

---

## 🎯 Conclusion

This project highlights how data analysis can be used to uncover hidden patterns in food delivery operations and provide actionable insights to improve efficiency and customer satisfaction.

---

