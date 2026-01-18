# 📊 Service Marketplace Analytics – QlikView Dashboard

## 📌 Project Overview
This project demonstrates the design and implementation of an **end-to-end analytics solution** built using a **dimensional data model** and visualized through **QlikView**.

The solution analyzes **service marketplace transactions and reviews**, providing insights into:
- Buyer behavior  
- Seller performance  
- Service categories  
- Revenue trends  
- Customer feedback  

The backend follows a **Star Schema (Fact–Dimension model)** optimized for analytical queries and BI reporting.

---

## 🏗️ Data Model Architecture
The project uses a **fact–dimension model** consisting of the following tables:

---

## ⭐ Fact Tables

### fact_transaction
Captures all service transactions.

**Measures & Attributes:**
- ServiceCost  
- PurchaseDate  
- PaymentMethod  

**Relationships:**
- Linked to Buyer, Seller, Service, and Time dimensions

---

### fact_review
Stores buyer reviews and ratings.

**Measures & Attributes:**
- Rating  
- ReviewDate  
- ReviewComment  

**Purpose:**
- Enables both qualitative and quantitative performance analysis

---

## 📐 Dimension Tables

### dim_service
- Service category  
- Price range  
- Service description  

### dim_buyer
- Buyer profile  
- Buyer location  

### dim_seller
- Seller profile  
- Experience level  
- Pricing range  

### dim_time
- Date  
- Day  
- Month  
- Quarter  
- Year  
- Weekday  

This structure enables **fast slicing, filtering, and aggregation** in BI tools like QlikView.

---

## 🧠 Dimensional Model Design (Star Schema)
The data model follows a **Star Schema** design where:

- Centralized **fact tables** store measurable business events  
- Surrounding **dimension tables** provide descriptive business context  

### Benefits:
- High query performance  
- Easy scalability  
- Clear business interpretation  
- BI-friendly structure  

---

## 📊 QlikView Dashboard Features
The QlikView dashboard built on this model provides the following insights:

---

## 🔹 Key KPIs
- Total Revenue  
- Number of Transactions  
- Average Service Cost  
- Average Ratings  
- Total Reviews Count  

---

## 🔹 Analytical Views
- Revenue by Service Category  
- Seller Performance Analysis  
- Buyer Location Distribution  
- Monthly & Yearly Transaction Trends  
- Ratings vs Revenue Comparison  
- Review Sentiment Overview (text-based insights)  

---

## 🔹 Interactivity
- Dynamic filters (Time, Category, Seller, Buyer)  
- Cross-filtering between charts  
- Drill-down analysis by date and category  
- Real-time KPI updates  

---

## 🛠️ Tools & Technologies
- **Data Modeling:** MySQL Workbench  
- **Visualization:** QlikView  
- **Design Approach:** Dimensional Modeling (Star Schema)  

---

## 📌 Key Learnings
- Designed a scalable analytical data model  
- Implemented fact–dimension relationships for BI reporting  
- Built interactive dashboards using QlikView  
- Applied best practices in dimensional modeling  

---

## ✅ Conclusion
This project showcases the complete lifecycle of a BI solution—from **data modeling** to **interactive analytics dashboards**—highlighting how structured data design enables meaningful business insights in service marketplace platforms.
