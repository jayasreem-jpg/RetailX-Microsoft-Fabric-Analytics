# RetailX – Microsoft Fabric Retail Analytics

## 📌 Project Overview

RetailX is an end-to-end retail analytics project built using Microsoft Fabric and Power BI.

The project demonstrates how retail data can be ingested, transformed, modeled, secured, and visualized using Microsoft Fabric.

## 🎯 Objective

To build a retail analytics solution that provides insights into sales, orders, products, stores, regions, and customer feedback.

## 📊 Dataset

- 50,000 retail orders
- Date range: January 2024 – December 2025
- 20 stores
- Customer data
- Product data
- Inventory data
- Customer feedback data

## 🏗️ Architecture

Source Data  
↓  
Bronze Lakehouse  
↓  
Silver Lakehouse  
↓  
Gold Lakehouse  
↓  
Semantic Model  
↓  
Power BI Dashboard

## 🛠️ Technologies Used

- Microsoft Fabric
- Lakehouse
- Dataflow Gen2
- Power Query / M
- SQL
- Spark / Notebooks
- Direct Lake
- Power BI
- DAX
- Row-Level Security (RLS)
- Deployment Pipelines

## 🔄 Data Engineering

The project uses a Bronze → Silver → Gold approach:

### Bronze
Raw ingested data.

### Silver
Cleaned and transformed data.

### Gold
Curated tables prepared for analytics and reporting.

## 📐 Semantic Model

A star-schema-based semantic model was created with fact and dimension tables.

The model includes relationships between:

- Orders
- Customers
- Products
- Stores
- Inventory
- Date

## 📈 Power BI Dashboard

The dashboard provides:

- Total Sales
- Total Orders
- Units Sold
- Average Order Value
- Average Rating
- Monthly Sales Trend
- Top 5 Products
- Top 5 Stores
- Sales by Category
- Sales by Region

## 🔐 Security

Implemented Row-Level Security (RLS) concepts to control data access based on user requirements.

## 🚀 Deployment

Practiced a Microsoft Fabric deployment workflow using separate environments:

Development → Test → Production

Deployment pipelines were used to move supported artifacts between environments.

## 💡 Key Insights

- South region recorded the highest sales.
- Electronics was the top-performing category.
- Store 20 recorded the highest sales among the stores analyzed.
- The dataset contains 50,000 orders across the 2024–2025 period.

## 📷 Dashboard Preview

Dashboard screenshots will be added to this repository.

## 📚 Key Learning

This project helped me gain hands-on experience with the complete analytics lifecycle in Microsoft Fabric, from data ingestion and transformation to semantic modeling, security, deployment, and Power BI reporting.
