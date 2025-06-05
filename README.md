# Task3_elevatelabs
# 📊 Walmart Sales Dashboard (Tableau)

An interactive Tableau dashboard that provides key insights from Walmart sales data. Designed for business stakeholders to monitor sales, customer behavior, and operational performance.

---

## 📁 Dataset

**Source**: `Generated_Walmart_Sales.csv`  
**Rows**: 1000  
**Attributes include**:
- Invoice ID, Branch, City, Customer Type, Gender
- Product Line, Unit Price, Quantity, Tax, Total
- Date, Time, Payment Method, COGS, Gross Margin %, Gross Income, Rating

---

## 🎯 Key KPIs (Displayed as Cards)

- ✅ **Total Sales** → `SUM(Total)`
- 💰 **Total Gross Income** → `SUM(gross income)`
- ⭐ **Average Rating** → `AVG(Rating)`
- 🧾 **Total Invoices** → `COUNT(Invoice ID)`

> Each KPI is shown in dashboard.

---

## 📈 Visualizations

### 1. **Monthly Sales Trend**
- **X-axis**: Date (Month/Year)
- **Y-axis**: SUM(Total)
- **Chart Type**: Line Chart
- **Filters**: City, Branch

### 2. **Sales by City**
- **Dimension**: City
- **Measure**: SUM(Total)
- **Chart Type**: Horizontal Bar Chart
- **Color**: Branch (optional)

### 3. **Product Line vs Sales & Gross Income**
- **Dimension**: Product line
- **Measures**: SUM(Total), SUM(gross income)
- **Chart Type**: Dual Axis Bar or Side-by-side Bars

### 4. **Customer Type & Gender Distribution**
- **X-axis**: Customer Type
- **Color**: Gender
- **Measure**: COUNT(Invoice ID)
- **Chart Type**: Stacked Bar Chart

### 5. **Payment Method Analysis**
- **Dimension**: Payment
- **Measure**: SUM(Total)
- **Chart Type**: Pie or Donut Chart

---

## 🔁 Filters (Slicers) for Interactivity

Global filters used in dashboard:
- 🏙️ **City**
- 🧑‍💼 **Customer Type**
- ⚥ **Gender**
- 🏢 **Branch**
- 📦 **Product Line**
- 📅 **Date**

These filters allow users to drill down and analyze specific segments.

---

## 🧩 Tools Used

- **📊 Tableau Desktop**
- **📷 PowerPoint** for summary documentation

---

## 📝 How to Use

1. Open the Tableau `.twbx` file (or recreate using this guide).
2. Explore KPIs and visualizations.
3. Use slicers to analyze specific branches, cities, and customer segments.

---

## 📎 Optional Files

- 🧾 `Generated_Walmart_Sales.csv` (Input Dataset)
- 📊 `Task3_Dashboard.twbx` (Tableau Dashboard)
- 📄 `Task_3_summary.pptx` (Presentation Summary)

---
