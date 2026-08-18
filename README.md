# 🛍️ RetailX – Microsoft Fabric Retail Analytics

> 🚀 **End-to-end retail analytics solution built with Microsoft Fabric and Power BI**

RetailX is an end-to-end retail analytics project that demonstrates how **Microsoft Fabric** can be used to ingest, transform, model, secure, deploy, and visualize retail data.

The project follows a modern **Bronze → Silver → Gold** architecture and uses a **star-schema semantic model** to deliver interactive Power BI analytics.

---

## 🎯 Project Objective

The objective of RetailX is to build a scalable retail analytics solution that provides actionable insights into:

* 💰 Sales performance
* 🛒 Orders and units sold
* 📦 Products and categories
* 🏪 Store performance
* 🌍 Regional sales
* 👥 Customer information
* ⭐ Customer feedback
* 📊 Business KPIs

---

## 📊 Dataset

| 📌 Data      | Details                          |
| ------------ | -------------------------------- |
| 🛒 Orders    | **50,000** retail orders         |
| 📅 Period    | **January 2024 – December 2025** |
| 🏪 Stores    | **20 stores**                    |
| 👥 Customers | Customer master data             |
| 📦 Products  | Product and category data        |
| 📋 Inventory | Inventory information            |
| ⭐ Feedback   | Customer feedback and ratings    |

---

## 🏗️ Solution Architecture

```text
             📥 Source Data
                  │
                  ▼
          🥉 Bronze Lakehouse
             Raw Data
                  │
                  ▼
          🥈 Silver Lakehouse
       Cleaned & Transformed Data
                  │
                  ▼
           🥇 Gold Lakehouse
        Curated Analytics Tables
                  │
                  ▼
          🧠 Semantic Model
          ⭐ Star Schema
                  │
                  ▼
          📊 Power BI Dashboard
```

---

## 🛠️ Technologies & Tools

### ☁️ Microsoft Fabric

* 🏞️ Lakehouse
* 🔄 Dataflow Gen2
* ⚙️ Data Pipelines
* 📓 Notebooks / Spark
* 🏢 Warehouse concepts
* 🧠 Semantic Models
* 🚀 Deployment Pipelines

### 📊 Analytics & BI

* 📈 Power BI
* 🧮 DAX
* 🔍 Power Query / M
* 🗃️ SQL
* ⚡ Direct Lake

### 🔐 Security & Deployment

* 🔒 Row-Level Security (RLS)
* 🚀 Dev → Test → Production deployment
* ⚙️ Deployment pipeline concepts

---

## 🔄 Data Engineering

RetailX follows the **Medallion Architecture**:

### 🥉 Bronze Layer – Raw Data

Contains data ingested from source systems with minimal transformation.

**Purpose:**

* 📥 Store raw data
* 🔄 Preserve source information
* 🗂️ Provide an initial landing layer

### 🥈 Silver Layer – Cleaned Data

Data is cleaned and transformed using Power Query, SQL, and Spark-based processing.

**Transformations include:**

* 🧹 Data cleansing
* 🔄 Data type transformations
* 🚫 Handling invalid records
* 🔗 Preparing relationships
* 📐 Standardizing business data

### 🥇 Gold Layer – Analytics Ready

Curated tables are prepared for reporting and analytics.

**Purpose:**

* 📊 Business-ready datasets
* ⚡ Optimized reporting
* 🧠 Semantic model consumption
* 📈 Power BI analytics

---

## 🧠 Semantic Model

A **star-schema-based semantic model** was created for analytical reporting.

### ⭐ Fact Table

* 🛒 **Orders**

### 📐 Dimension Tables

* 👥 **Customers**
* 📦 **Products**
* 🏪 **Stores**
* 📦 **Inventory**
* 📅 **Date**

The relationships between fact and dimension tables enable efficient filtering, slicing, and aggregation across the report.

---

## 📈 Power BI Dashboard

The Power BI dashboard provides an interactive view of retail performance.

### 💰 Key KPIs

* 💵 **Total Sales**
* 🛒 **Total Orders**
* 📦 **Units Sold**
* 🧾 **Average Order Value**
* ⭐ **Average Rating**

### 📊 Business Analysis

* 📅 Monthly Sales Trend
* 🏆 Top 5 Products
* 🏪 Top 5 Stores
* 🗂️ Sales by Category
* 🌍 Sales by Region
* ⭐ Customer Feedback Analysis

---

## 🔐 Security

Implemented **Row-Level Security (RLS) concepts** to demonstrate how access to retail data can be restricted according to business requirements.

For example, users can be configured to view only the data relevant to their assigned region.

---

## 🚀 Deployment

A **Development → Test → Production** deployment workflow was practiced using Microsoft Fabric Deployment Pipelines.

```text
🛠️ DEVELOPMENT
       │
       ▼
🧪 TEST
       │
       ▼
🚀 PRODUCTION
```

The workflow demonstrates how supported Fabric artifacts can be promoted across different environments while maintaining separate workspace stages.

---

## 💡 Key Business Insights

📍 **South Region** recorded the highest sales among the regions analyzed.

📱 **Electronics** was the top-performing product category.

🏪 **Store 20** recorded the highest sales among the stores analyzed.

🛒 The dataset contains **50,000 orders** covering the **2024–2025** period.

---

## 📷 Dashboard Preview

Dashboard screenshots will be added here.

```text
📊 Power BI Dashboard
┌─────────────────────────────────────────────┐
│ 💰 Sales   🛒 Orders   📦 Units   ⭐ Rating │
├─────────────────────────────────────────────┤
│                                             │
│       📈 Monthly Sales Trend                │
│                                             │
├──────────────────────┬──────────────────────┤
│ 🏆 Top Products      │ 🏪 Top Stores        │
├──────────────────────┼──────────────────────┤
│ 🗂️ Category Sales    │ 🌍 Regional Sales    │
└──────────────────────┴──────────────────────┘
```

---

## 📚 Key Learning

Through RetailX, I gained hands-on experience across the **end-to-end Microsoft Fabric analytics lifecycle**:

**📥 Data Ingestion → 🔄 Transformation → 🏞️ Lakehouse → 🧠 Semantic Modeling → 🔐 Security → 🚀 Deployment → 📊 Reporting**

The project strengthened my practical understanding of **Microsoft Fabric, Power BI, SQL, DAX, Power Query, Direct Lake, RLS, Medallion Architecture, Star Schema, and Deployment Pipelines**.

---

## 🌟 Project Highlights

✨ **50,000+ retail orders**

🏗️ **Bronze → Silver → Gold architecture**

⭐ **Star-schema semantic model**

⚡ **Direct Lake**

🔐 **Row-Level Security concepts**

🚀 **Dev → Test → Production deployment**

📊 **Interactive Power BI analytics**

🧩 **End-to-end Microsoft Fabric project**
