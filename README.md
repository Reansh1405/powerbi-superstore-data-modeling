# 📊 Superstore Data Modelling in Power BI

## 📌 Project Overview

This project demonstrates the implementation of a structured **data model in Power BI** using the **Sample Superstore** dataset. The primary objective was to transform raw transactional data into an optimized analytical model by creating dimension tables, defining relationships, and implementing a dedicated Calendar table for time-based analysis.

The final model follows the **Star Schema** approach, ensuring efficient data organization and improved reporting performance.

---

## 🎯 Project Objectives

- Import and prepare the Superstore dataset
- Create Dimension Tables
- Build One-to-Many Relationships
- Implement a Star Schema
- Develop a Calendar Table using DAX
- Create a Date Hierarchy
- Validate the Data Model

---

## 📂 Dataset

The project uses the **Sample Superstore** dataset, which contains detailed information about:

- Customer Information
- Product Details
- Regional Data
- Sales Transactions
- Order & Shipping Details
- Profit and Discount

**Dataset Location**

```text
Dataset/
└── sample-superstore.csv
```

---

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling

---

## 🏗️ Data Model

The data model consists of one **Fact Table** and multiple **Dimension Tables**, organized using a **Star Schema**.

### Relationships Created

| Dimension Table | Fact Table | Relationship Key |
|-----------------|------------|------------------|
| Customers | Orders | Customer ID |
| Products | Orders | Product Key |
| Regions | Orders | Region |
| Calendar | Orders | Order Date |

### Relationship Configuration

- **Cardinality:** One-to-Many (1:*)
- **Cross Filter Direction:** Single
- **Active Relationships:** Enabled

---

## 📅 Calendar Table

A dedicated Calendar table was created using DAX to support efficient date-based analysis.

### Calendar Attributes

- Year
- Quarter
- Month
- Month Number
- Day

A Date Hierarchy was also created to enable drill-down analysis across different time levels.

---

## ✨ Key Features

- ⭐ Star Schema Design
- 📊 Fact & Dimension Tables
- 🔗 Relationship Management
- 📅 Calendar Table using DAX
- 📆 Date Hierarchy
- ✅ Data Validation
- ⚡ Optimized Data Model for Reporting

---

## 📁 Repository Structure

```text
Powerbi-Superstore-Data-Modelling/
│
├── Superstore_Data_Modelling.pbix
├── README.md
│
├── Dataset/
  └── sample-superstore.csv
```

---

## 📚 Learning Outcomes

This project helped strengthen my understanding of:

- Data Modeling in Power BI
- Star Schema Design
- Creating Fact & Dimension Tables
- Building One-to-Many Relationships
- Power Query for Data Preparation
- Writing DAX for Calendar Tables
- Creating Date Hierarchies
- Data Validation Techniques
- Best Practices for Building Scalable Data Models

---

## 🚀 Getting Started

1. Clone this repository.
2. Open **Superstore_Data_Modelling.pbix** using Microsoft Power BI Desktop.
3. Refresh the dataset if required.
4. Explore the data model and relationships.

---

## 👨‍💻 Author

**Reansh Singh**

Aspiring Data Analyst | Power BI | SQL | Python | Excel | Tableau

If you found this project useful, consider giving it a ⭐ to support the repository.
