# Power-BI-Project_2
an interactive dashboard created in Power BI using data transformation in power query and DAX formulae. Gives key insights on Blinkit's sales performance, customer satistifaction and inventory distribution to find oppurtunities for optimization using various visualizations in Power BI
# 📊 Blinkit Sales Performance Dashboard

An interactive **Power BI dashboard** designed to analyze and visualize Blinkit's sales performance across outlet types, outlet sizes, item categories, fat content, outlet locations, and establishment trends.

The project demonstrates the use of **Power BI, DAX, data visualization, KPI development, and business-oriented data analysis** to transform raw retail data into an interactive analytical dashboard.

> **Note:** This is a data analytics/visualization project created for portfolio and learning purposes and is not affiliated with Blinkit.

---

## 📌 Project Overview

The objective of this project is to analyze retail sales data and identify patterns in:

- Overall sales performance
- Item and outlet performance
- Outlet establishment trends
- Outlet size and location
- Item categories
- Fat-content distribution
- Average ratings
- Outlet-type performance

The dashboard provides an interactive interface where users can filter the analysis by:

- **Outlet Location Type**
- **Outlet Size**
- **Item Type**

This allows the user to explore how different outlet and product characteristics affect sales performance.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and visualization |
| **Power Query** | Data transformation and preparation |
| **DAX** | KPI and metric calculations |
| **Data Modeling** | Organizing fields and measures |
| **GitHub** | Project documentation and portfolio |

---

## 📊 Key Performance Indicators

The dashboard uses **DAX measures** to calculate and display key business metrics.

### Total Sales
**₹1.20M**

Represents the total revenue generated across the available sales records.

### Number of Items
**8,523**

Represents the total quantity of items sold.

### Average Sales
**₹141**

Represents the average sales value calculated across the relevant sales records.

### Average Rating
**3.92**

Represents the average customer rating associated with the products/outlets.

---

## 🧮 DAX & Metrics

DAX (Data Analysis Expressions) was used to create calculated measures for the dashboard's KPI cards and analytical visuals.

Examples of the types of metrics developed include:

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
No. of Items = SUM('BlinkIT Grocery Data'[No. of Items])
Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
