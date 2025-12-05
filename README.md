
# 🍴 OMATO Food Delivery Dashboard Report – Power BI

📘 **Project Overview**

This project is an Interactive Power BI Dashboard built on OMATO Food Delivery Data to analyze and visualize key business insights related to sales, transactions, and delivery performance.

With the help of DAX formulas, the dashboard provides detailed analysis across multiple dimensions such as Food Type, Member Type, Payment Mode, and Restaurant Type — helping to understand customer behavior and sales patterns effectively.

🗂️ **Repository Contents**

**File Name Description**

1. OMATO_Food_Delivery_Dashboard_Report.pbix Power BI project file containing the interactive dashboard.

2. OMATO_Data.xlsx Main dataset containing consolidated OMATO data.

3. January_2023_Sales.xlsx Monthly sales data for January 2023.

4. February_2023_Sales.xlsx Monthly sales data for February 2023.

5. March_2023_Sales.xlsx Monthly sales data for March 2023.

6. April_2023_Sales.xlsx Monthly sales data for April 2023.

7. OMATO_Food_Delivery_Dashboard_Report.png Image preview of the dashboard.

📊 **Dashboard Insights**

The dashboard reveals a variety of meaningful insights through multiple charts and metrics:

🔹 **Key Metrics**

✅Total Quantity: 15K

✅Total Transactions: 3K

✅Average Quantity: 5.50

🔹 **Visual Insights**

1️⃣Total Quantity by Month: Trend analysis of food quantity sold from January to April.

2️⃣Total Quantity by Food Type: Top-selling food items such as Samosa, Butter Chicken, Chole Bhature, and Masala Dosa.

3️⃣Transactions by Month: Monthly transaction trends highlighting sales growth and decline.

4️⃣Transactions by Delivery Status: Comparison between Delivered and Cancelled orders.

5️⃣Transactions by Payment Method: Distribution of payments via UPI, COD, and Card.

6️⃣Transactions by Food Type & Member Type: Comparison of Gold and Regular members across food categories.

⚙️ **Tools & Technologies Used**

👉🏻Microsoft Power BI – For interactive dashboard creation and visualization

👉🏻Microsoft Excel – For data preparation and source files

👉🏻DAX (Data Analysis Expressions) – For calculated columns and key performance metrics

🧮 **Key DAX Measures Used**

Some of the DAX formulas applied in this project include:

✅Total Quantity = SUM(Data[Quantity])

✅Total Transactions = DISTINCTCOUNT(Data[Transaction_ID])

✅Average Quantity = AVERAGE(Data[Quantity])

✅Delivered Orders % = DIVIDE([Delivered Orders], [Total Orders])

✅Month-wise Sales = CALCULATE(SUM(Data[Quantity]), Data[Month])

These DAX measures help generate accurate and dynamic KPIs used throughout the dashboard.

🧠 **Learning & Takeaways**

💠Learned to clean, model, and visualize data in Power BI

💠Created interactive filters and slicers for better data exploration

💠Practiced building custom KPIs using DAX formulas

💠Enhanced ability to communicate business insights visually

🖼️ **Dashboard Preview**

<img src="https://github.com/sahelinath22/OMATO-Food-Delivery-Dashboard-Report-Project/blob/6f800117a58543c55ce002bc00d8cab561aad257/OMATO%20Food%20Delivery%20Dashboard%20Report%20by%20SAHELI%20NATH.png" alt="Image Description" width="600">

🚀 **How to Use**

👉🏻Download or clone this repository to your system.

👉🏻Open the file OMATO_Food_Delivery_Dashboard_Report.pbix in Microsoft Power BI Desktop.

👉🏻Ensure all data files (Excel sheets) are available in the same directory.

👉🏻Explore the dashboard interactively using filters for:

✅Food Type 🍔

✅Member Type 👤

✅Payment Mode 💳

✅Restaurant Type 🍽️

👩‍💻 **Author**

Saheli Nath

📧**Linkedin Profile:** [https://www.linkedin.com/in/saheli-nath28/]

**Email:** [nathsaheli1999@gmail.com]

⭐ **Acknowledgment**

This project was created as part of my Power BI learning journey, demonstrating the application of DAX, data modeling, and visualization techniques to extract insights from food delivery data.

If you found this project useful or inspiring, don’t forget to ⭐ star this repository!



