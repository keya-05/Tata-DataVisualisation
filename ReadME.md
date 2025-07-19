# Tata Data Visualisation – Task 3

This project is a part of the **Tata Data Visualisation Virtual Experience Program** on the Forage platform. The task involves analyzing retail transaction data to generate insights using **Tableau** and creating a visual dashboard for presentation.

---

##  Objective

To explore customer demand, revenue trends, and top-performing regions and customers by:
- Cleaning and filtering the retail dataset
- Creating calculated fields and KPIs (e.g., Revenue)
- Visualizing the business insights via interactive dashboards
- Understanding customer distribution and behavior across countries

---

##  Tools Used

- **Tableau** (for data visualization and dashboard creation)
- **Microsoft Excel** (for initial dataset exploration)

---

##  Dashboard Preview

<img width="1227" height="1027" alt="image" src="https://github.com/user-attachments/assets/78b3676f-219d-4aae-835e-e5ee761597b6" />

---

##  Visualizations and Insights

### 1. **Demand by Country (Map)**
- A **filled map** showing customer demand (Quantity and Revenue) across the globe.
- Darker shades represent higher total orders and revenue.
- UK and Western Europe showed the highest retail activity.

---

### 2. **Revenue and Quantity by Top 10 Countries (Bar Chart)**
- Highlights the **top 10 countries** by both Quantity sold and Revenue generated.
- Countries like **Netherlands, Germany, and France** show a balance between units sold and revenue earned.
- Helps identify markets with high-value customers.

---

### 3. **Top 10 Customers by Revenue**
- A bar chart showing which **Customer IDs** contributed the most revenue.
- The customer with ID `14646` is the highest spender.
- The chart includes a “Null” category, which may represent guest checkouts or unidentified users.

---

### 4. **Time Series of Revenue in 2011**
- A monthly line chart (in another tab) shows revenue trends across 2011.
- Reveals seasonal spikes in revenue, especially before holidays.

---

##  Key Calculated Fields Used

- `Revenue = Quantity * UnitPrice`
- Filters: Quantity ≥ 1 and UnitPrice ≥ 0
- Year filtered to 2011 for time-series analysis

---

##  Final Deliverables

- Tableau Packaged Workbook (.twbx)
- Cleaned and filtered visual dashboard
- README for documentation and understanding

---

