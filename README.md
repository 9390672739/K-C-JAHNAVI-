🏠 Housing Market Trends Analysis Dashboard

📌 Project Overview
This project analyzes housing market data using Tableau to identify trends in house prices, renovation impact, house age distribution, and property features.

An interactive dashboard and story were created in Tableau and published to Tableau Public. The dashboard is also embedded into a Flask web application for web integration.




🎯 Problem Statement
To analyze housing market trends and understand how factors such as renovation years, house age, number of bedrooms, bathrooms, floors, and basement area affect sale prices.





📊 Dataset Description
Total Records: 21,609
File Type: CSV
Dataset Size: (Add your file size here e.g., 3.2 MB)
Source: Kaggle Housing Dataset


🛠 Tools & Technologies Used
Tableau Desktop
Tableau Public
Python
Flask
HTML
GitHub



📈 Data Preparation


Connected Tableau to CSV dataset
Created calculated fields:
Price Category (Low / Medium / High)
Renovation Group (Recently Renovated / Old Renovation)
Applied Top-N filters:
Sale Price Top 10
House Age Top 10


📊 Visualizations Created (6 Sheets)
Count of Houses (KPI)
Average Sale Price (KPI)
Total Basement Area (KPI)
Sale Price vs Renovation Years (Histogram)
House Age vs Renovation Status (Pie Chart)
House Age vs Features (Bathrooms / Bedrooms / Floors - Bar Charts)



📌 Dashboard
A comprehensive dashboard combining all visualizations:

KPI Cards (Top Row)
Histogram (Middle)
Pie Chart + Feature Comparison (Bottom)
Interactive filters enabled
📖 Story (5 Scenes)
Dataset Overview
Sales vs Renovation Years
House Age vs Renovation Status
House Age vs Features
Final Insights



⚡ Performance Testing
Total records loaded: 21,609
Dataset size: (Add your file size)
Applied Top-N filters for optimized analysis
Created 2 calculated fields for enhanced categorization


🌐 Tableau Public Dashboard


🔗 Dashboard Link: https://public.tableau.com/shared/QNGNJ4T4D?:display_count=n&:origin=viz_share_link

🧩 Flask Web Integration
The Tableau dashboard is embedded into a Flask web application.

Folder Structure:
flask_app/ app.py templates/ index.html

To run the Flask app:

pip install flask python app.py

✅ Project Highlights
✔ 6 Tableau Sheets
✔ 1 Interactive Dashboard
✔ 1 Story (5 Scenes)
✔ 2 Top-N Filters
✔ 2 Calculated Fields
✔ Published to Tableau Public
✔ Embedded using Flask

📌 Conclusion
The analysis shows that renovation status and property features significantly influence housing prices. Recently renovated houses tend to show different pricing patterns compared to older properties. Feature comparison across house age groups helps identify buyer preferences and market trends.

👤 Author
Your Name
K C JAHNAVI
