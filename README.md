# Quick_Bite_Food_Delivery
Quick Bite Food Delivery Analytics Dashboard serves as a practical example of how Power BI can be leveraged to solve real-world business challenges by delivering actionable insights that help organizations optimize performance, increase profitability, and provide a better customer experience.

Step 1: Data Understanding & Data Model Setup
Data Sources: Raw transactional data in Excel (Quick_Bite.xlsx) containing multiple relational tables (Customer Details, Food_Details, Resturant_Details, and Sales Data).

Star Schema Modeling:

Fact Table: Sales Data (contains order details, dates, quantities, delivery status, and payment methods).

Dimension Tables: Customer Details (customer name, membership level), Food_Details (item name, food type), and Resturant_Details (restaurant name, cuisine type).

Relationships: Configured 1-to-Many relationships from Dimension tables to the Sales Fact table using key columns (customer_id, Fooditem, Resturant_ID).
