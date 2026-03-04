# 📊 Hospitality Business Performance Dashboard (Power BI)

##  Project Overview

This project presents an interactive **Power BI dashboard** designed to analyze hospitality business performance across multiple hotels, cities, room categories, and booking platforms.

The dashboard provides insights into revenue trends, occupancy rates, booking patterns, and operational efficiency to support data-driven business decision-making.

---

##  Business Objectives

- Analyze total revenue performance  
- Track booking trends over time  
- Identify top-performing hotels  
- Compare room category revenue contribution  
- Evaluate booking platform effectiveness  
- Measure occupancy rate and ADR  
- Analyze customer ratings and cancellations  

---

##  Dataset Structure

The project follows a **Star Schema Data Model** using the following tables:

- `fact_bookings`
- `fact_aggregated_bookings`
- `dim_date`
- `dim_hotels`
- `dim_rooms`

Proper relationships were created between fact and dimension tables to enable accurate filtering and analysis.

---

##  Tools & Technologies Used

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Power Query (Data Cleaning & Transformation)  
- Data Modeling (Relationships & Schema Design)  

---

##  Key DAX Measures Created

- **Total Revenue**
- **Total Bookings**
- **Successful Bookings**
- **Occupancy %**
- **ADR (Average Daily Rate)**
- **Average Rating**
- **Cancellation %**

---

##  Dashboard Pages

###  1️ Executive Overview (Home Page)

- KPI Summary Cards  
- Monthly Revenue Trend  
- Navigation Buttons  

Provides a quick high-level summary of overall business performance.

---

### 2️ Business Performance

- Revenue by Hotel  
- Revenue by Room Category  
- Revenue by Booking Platform  
- Monthly Revenue Trend  
- Interactive Slicers  

This page delivers detailed revenue analysis to identify key performance drivers.

---

### 3 Hotel & Room Insights

- Average Rating by Hotel  
- Occupancy % by Hotel  
- Cancellation Analysis  
- Operational Performance Trends  

Focused on operational efficiency and customer experience insights.

---

##  Key Insights Derived

- Identified top revenue-generating hotels  
- Analyzed seasonal revenue patterns  
- Compared performance across room categories  
- Evaluated booking platform contributions  
- Measured occupancy efficiency and pricing strategy  

---

##  Dashboard Preview

<img width="1417" height="741" alt="Screenshot 2026-03-01 133526" src="https://github.com/user-attachments/assets/a301dc09-d7b9-41b3-83b2-c5b7a5c3a546" />

<img width="1320" height="740" alt="Screenshot 2026-03-01 133605" src="https://github.com/user-attachments/assets/51ee0f68-b707-4e9a-8291-b55cf20e8bee" />

<img width="1326" height="742" alt="Screenshot 2026-03-01 133629" src="https://github.com/user-attachments/assets/ae01e741-3e7c-4ee8-8ade-58e1c27b4f8c" />


##  How to Use

1. Download the `.pbix` file  
2. Open it in Power BI Desktop  
3. Use slicers for interactive filtering  
4. Navigate between pages for detailed insights  




---

⭐ If you found this project helpful, feel free to give it a star!
