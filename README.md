# Car Sales Dataset Analysis Report

## 1. Introduction to the Dataset

The dataset used in this project was sourced from [kaggle](https://www.kaggle.com/datasets/msnbehdani/mock-dataset-of-second-hand-car-sales), a platform widely recognized for hosting high-quality datasets used in data science and machine learning projects.

It contains detailed information on **car sales listings**, with each row representing an individual listing and columns capturing key attributes such as:

* **Manufacturer** – Car brand (e.g., Toyota, Ford, VW).
* **Model** – Specific car model within the manufacturer’s lineup.
* **Year of Manufacture** – Year the car was produced, which directly affects depreciation and market value.
* **Mileage** – Distance the car has been driven, typically in kilometers.
* **Fuel Type** – Engine type (e.g., Petrol, Diesel, Hybrid).
* **Price** – Listed market value of the car.

This dataset is valuable because it enables analysis of pricing trends, consumer demand by brand or year, and the influence of mileage and fuel type on car values. Kaggle was selected as the source because it offers structured, reliable, and diverse datasets that support reproducible data analysis.

---

## 2. Power BI Dashboard Overview

A **Power BI dashboard** was created to visualize this dataset (based on the dashboard image provided). It includes:

* **Summary Cards** → Total listings, unique manufacturers, and average prices.
* **Bar Charts** → Top manufacturers and models.
* **Pie Charts** → Share of car types.
* **Line Charts** → Yearly trend of car listings.
* **Interactive Tables** → Drill-down for detailed exploration.

This dashboard provides quick, high-level insights, making it suitable for stakeholders who prefer visual summaries.

<img width="577" height="325" alt="car sales analysis dashboard" src="https://github.com/user-attachments/assets/6bb2db16-77bf-4ed0-9426-dd39eb602e14" />


## 3. Project Objective

The objective of this project was to transform raw car sales data into actionable insights using two complementary approaches:

1. **Python-based Exploration** → An interactive lookup tool and chart generator for detailed, step-by-step analysis.
2. **Power BI Dashboard** → A visual storytelling platform for non-technical users to grasp market trends quickly.

Together, these approaches make the dataset accessible, interpretable, and useful for decision-making.

---

## 4. Unique Aspects of the Project

* Interactive **car lookup tool** limited to valid dataset entries.
* **Step-by-step exploration** that guides users from manufacturer to specific details.
* **Neutral recommendations** (e.g., average vs dataset pricing).
* Dual analysis through **Python exploration** and **Power BI visualization**.

---

## 5. Insights Uncovered

* Popular manufacturers dominate listings (Toyota, Honda, Mercedes, etc.).
* Price distribution shows many affordable cars, but also luxury outliers.
* Mileage strongly affects value, though premium brands depreciate slower.
* Petrol remains the most common fuel type, with diesel and hybrid making up smaller shares.
* Specific years stand out as peaks in listings, likely due to import or resale trends.

---

## 6. Problems Solved

* **Manual filtering inefficiency** → solved by interactive lookup.
* **Hidden market trends in raw data** → revealed through charts and Power BI visuals.
* **User errors** → prevented by dataset-restricted inputs.

---

## 7. Key Findings & Recommendations

* **Buyers**: Use lookup to ensure fair negotiations when prices exceed dataset averages.
* **Sellers**: Highlight cars with low mileage as premium-value offerings.
* **Analysts**: Extend analysis with dimensions such as geography or transmission type for deeper insights.

---

## 8. Conclusion

This project successfully transforms a Kaggle car sales dataset into a **decision-support system** by merging **Python interactivity** with **Power BI visualization**. It benefits buyers, sellers, and analysts alike, providing both granular insights and high-level summaries.

---

## 9. How to Navigate the Python Code

### A. Interactive Lookup Tool

* Run the lookup cell.
* Input details step by step: **Manufacturer → Model → Year → Fuel Type**.
* Receive outputs on listings, prices, mileage, and fuel availability.
* Decide whether to continue exploring or stop.

### B. Chart Visualization Tool

* Run the chart cell.
* Automatically generates charts on manufacturers, prices, mileage, and fuel type distribution.

### C. Exit and Control

* Press **Enter** to quit at any step.
* Type **yes/no** when asked if you want to continue exploring.

---

## 10. Power BI vs Python

* **Python** → Great for interactive, detailed exploration.
* **Power BI** → Best for quick storytelling and presentations.

By combining both, the project ensures flexibility for different types of users.





