# 📊 Evaluating GDP per Capita using CASE and IF
© ExploreAI Academy 
Adopted by Ibrahim Ambale

This notebook demonstrates how to calculate and categorize GDP per capita using SQL `IF` and `CASE` statements. The analysis uses the `Access_to_Basic_Services` table from the `united_nations` MySQL database.

⚠️ Important:
This notebook will not run on Google Colab as it requires a connection to a local MySQL database. Ensure it is executed on the same machine as your MySQL Workbench installation and the `united_nations` database.

---
## 🎯 Learning Objectives
By the end of this notebook, you will be able to:

  - Understand the concept and significance of GDP per capita in evaluating economic conditions.
  
  - Write SQL queries to calculate GDP per capita.
  
  - Use `IF` and `CASE` statements to classify countries based on GDP per capita thresholds.

---
## 📘 Overview
GDP per capita is calculated as:
```
GDP per capita = Estimated GDP (in billions) / Estimated Population (in millions) × 1000
```
This measure provides insights into average economic productivity per person and is commonly used to assess living standards and economic development across countries and time periods.

In this notebook, you'll:

  - Connect to a MySQL database using Python (`mysql` and `pymysql` connectors).
  
  - Perform calculations directly in SQL.
  
  - Apply conditional logic using `IF` and `CASE` to group countries into income categories such as `'Low'`, `'Medium'`, and `'High'`.

---
## 🧮 Tools & Technologies
- SQL (MySQL)

- Python (Jupyter Notebook)

- mysql.connector or pymysql

- MySQL Workbench

---
## 🗃️ Dataset
Table: united_nations.Access_to_Basic_Services
Key Columns Used:

  - `Country_name`
  
  - `Time_period`
  
  - `Est_population_in_millions`
  
  - `Est_gdp_in_billions`

---
## 🏁 Getting Started
To run this notebook successfully:

1. Ensure MySQL Workbench and the united_nations database are set up on your local machine.

2. Install required packages using pip:
```
pip install pymysql sqlalchemy
```
3. Update the database connection details in the notebook.

4. Run the cells sequentially.

---
## ✅ Outputs
- GDP per capita and GDP per capita per day values.

- Poverty line thresholds applied based on year.

- Countries grouped into Income Categories using CASE and IF.

---
## 📌 License
This project is for educational purposes and is © ExploreAI Academy.



