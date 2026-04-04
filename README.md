# Infosys SpringBoot 
# Project :Hotel Revenue AI – Power BI Dashboard Project
#  A.Veda Varshini, Group-1, Bactch-13 , Team -D.

##  Project Overview
The Hotel Revenue AI project focuses on analyzing hotel booking data to understand revenue performance, customer behavior, and revenue optimization. The project uses Power BI to convert raw data into interactive dashboards that support data-driven decision-making in the hospitality domain.

---

##  Objectives
- Analyze overall hotel revenue performance  
- Identify booking trends and seasonal demand patterns  
- Understand customer behavior and retention  
- Evaluate pricing strategy using Average Daily Rate (ADR)  
- Support revenue optimization using analytical insights  

---

##  Tools & Technologies
- Power BI (Visualization & Dashboard)  
- DAX (Data Analysis Expressions)  
- Power Query (Data Cleaning & Transformation)  
- Excel Dataset  

---

##  Dataset Description
The dataset contains hotel booking information including:
- Booking details (Arrival Date, Lead Time)  
- Customer information (Country, Customer Type)  
- Room details (Room Type, Nights, Guests)  
- Pricing and revenue (ADR, Revenue)  
- Booking status (Cancellation, Changes)  

---

##  Data Cleaning & Preparation
- Removed missing and duplicate values  
- Converted columns to proper data types  
- Standardized column names  
- Cleaned date fields for time analysis  

---

##  Data Modeling
- Created a Calendar table for time-based analysis  
- Established relationship:
  Calendar[Date] → Hotel_data[Arrival Date]  
- Applied star schema model  
- Created calculated columns such as Year, Month, and YearMonth  

---

## DAX Measures
Key measures created:
- Total Revenue  
- Total Bookings  
- Avg ADR  
- Total Guests Count  
- Cancellation Rate  
- Revenue per Night  
- Repeat %  
- Occupancy Proxy  

---

## Dashboards Developed

### 1. Revenue Performance Dashboard
- Displays overall revenue, bookings, ADR, and guest count  
- Shows revenue trends over time  
- Analyzes market segments and distribution channels  
- Identifies room type performance  

---

### 2. Customer and Booking Behavior Dashboard
- Analyzes total customers and repeat customers  
- Studies lead time and booking patterns  
- Identifies top countries contributing bookings  
- Evaluates customer types and behavior  

---

### 3. Revenue Optimization and AI Insights Dashboard
- Evaluates revenue per night and occupancy  
- Analyzes demand index and pricing trends  
- Studies lead-time impact on revenue  
- Identifies high-demand room categories  

---

## Key Insights
- Revenue shows seasonal variation with peak months  
- Online travel agencies contribute most bookings  
- Transient customers dominate hotel demand  
- Repeat customer percentage is relatively low  
- Early bookings generate higher revenue  
- Certain room types contribute more to demand  

---

## Business Value
- Enables tracking of revenue and booking performance  
- Supports pricing optimization using ADR trends  
- Helps identify profitable customer segments  
- Improves decision-making using data insights  
- Assists in demand forecasting and resource planning  

---

## Future Scope
- AI-based demand forecasting  
- Dynamic pricing models  
- Customer churn prediction  
- Real-time data integration  

---

## Conclusion
This project demonstrates how data analytics and Power BI dashboards can transform hotel booking data into actionable insights, enabling better revenue management, improved customer strategies, and optimized business performance.

---

## 👩‍💻 Author
Veda Varshini  
Group – 1 (Batch-13)
