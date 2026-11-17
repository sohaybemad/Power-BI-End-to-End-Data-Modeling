# Power BI End-to-End Data Modeling Project

## Project Overview

This project demonstrates an end-to-end **Power BI Data Modeling** workflow, transforming **23 complex, interconnected source tables** into a clean, structured, and scalable **dimensional data model**.

The objective was to apply data modeling best practices to improve data organization, relationships, accuracy, and maintainability.

## Tools & Technologies

- **Power BI Desktop** – Data modeling and semantic model development
- **Power Query** – Data cleaning and transformation
- **DAX** – Business calculations and measures
- **Star Schema** – Dimensional modeling architecture
- **Row-Level Security (RLS)** – Data access control

## Project Implementation

- **Data Exploration:** Analyzed 23 source tables and identified structural complexities and relationship issues.
- **Data Transformation:** Cleaned and organized source data using Power Query.
- **Dimension Modeling:** Structured Customer, Product, Campaign, Date, Geography, and Order Flags dimensions.
- **Fact Modeling:** Organized Sales, Inventory, Order Process, Promotion Coverage, Campaign Spend, and Sales Targets fact tables.
- **Dimensional Modeling:** Established relationships between fact and dimension tables, including active and inactive relationships.
- **DAX:** Organized analytical measures in a dedicated measures table.
- **Security:** Added a dedicated security table connected to the Customer dimension.

## Data Model Transformation

### Before: Original Complex Data Model
<img width="1503" height="915" alt="image" src="https://github.com/user-attachments/assets/d4306777-b54e-4071-97eb-1af9bd1f53bf" />


### After: Optimized Dimensional Data Model

![Optimized Data Model](screenshots/Data_Model_After_Optimization.png)

## Project Outcome

Transformed a complex source data structure into an organized Power BI semantic model containing:

- **6 Fact Tables**
- **6 Dimension Tables**
- **1 Security Table**
- **1 Dedicated Measures Table**

This project strengthened my practical understanding of **Power Query, Dimensional Modeling, Star Schema Design, DAX, and relationship management**.

## Acknowledgments

This project was completed as a hands-on implementation of the **Power BI Data Modeling Portfolio Project** tutorial by **Baraa Khatib Salkini (Data With Baraa)**.

**Original Tutorial:** https://youtu.be/0A2k62YEbfI

---

**Technologies:** Power BI | Power Query | DAX | Dimensional Modeling | Star Schema | RLS
