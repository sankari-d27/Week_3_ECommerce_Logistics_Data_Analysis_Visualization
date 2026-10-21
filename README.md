##Week 3: E-Commerce Logistics Data Analysis

###Project Overview

This project focuses on analyzing e-commerce logistics data using Python and Power BI. The goal is to understand product demand, inventory levels, delivery performance, and shipping costs.

###Project_Link:https://github.com/sankari-d27/Week_3_ECommerce_Logistics_Data_Analysis_Visualization/ 

###This project was completed as part of my YuvaIntern internship.

###Objectives

Analyze product demand and order values.
Check inventory levels and reorder requirements.
Compare delivery partner performance.
Analyze shipping costs.
Create charts and dashboards to understand logistics performance.
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Power BI
Jupyter Notebook
Dataset

The dataset initially contained 71 records and 15 columns. After removing one duplicate order ID, 70 unique orders were used for analysis.

The dataset includes order dates, product categories, order values, shipping costs, warehouses, delivery partners, delivery times, inventory levels, and customer ratings.

Data Cleaning
Removed one duplicate order ID.
Identified missing values.
Found an invalid negative order value.
Excluded invalid delivery durations from delivery analysis.
Identified an unusually high shipping cost for further investigation.
Key Findings
Unique Orders: 70
Total Order Value: ₹8,78,300
Average Delivery Time: 3.35 days
Late Delivery Rate: 22.06%
Average Customer Rating: 4.04/5
Inventory Reorder Alert Rate: 68.12%
Main Insights
Electronics generated the highest recorded order value.
Mumbai had the highest reorder alert rate at 92.31%.
Ecom Express had the highest late-delivery rate at 39.13%.
One shipment had an unusual shipping cost of ₹25,000 that needs verification.
Recorded order value decreased from January to March 2026.
Visualizations

###The project includes charts for:

Orders by product category
Order value by category
Inventory by warehouse
Reorder alert rates
Delivery partner performance
Shipping cost distribution
Monthly order-value trends
Correlation between logistics metrics
Business Recommendations
Improve inventory planning for high-demand products.
Review stock levels at the Mumbai warehouse.
Investigate delays associated with Ecom Express.
Verify unusual shipping charges.
Monitor logistics performance regularly.
How to Run
Download or clone the repository.
Install the required libraries:
pip install pandas numpy matplotlib seaborn jupyter

Open the Jupyter Notebook.
Load the dataset.
Run the code to generate the analysis and charts.

###Conclusion

This project helped me understand how Python and Power BI can be used to analyze logistics data. The findings can help improve inventory management, delivery performance, and shipping cost control.

Author
Sankari D

Internship: YuvaIntern

Project: Data-Driven Inventory Management and Delivery Optimization for an E-Commerce Logistics Company
