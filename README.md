# 🛒 Blinkit Data Analytics Dashboard

## 📊 Project Overview

This project is an **interactive Power BI dashboard** developed to analyze Blinkit's sales and outlet performance. The dashboard transforms raw sales data into meaningful business insights through interactive visualizations, KPIs, filters, and comparative analysis.

The objective of this project is to understand **sales performance, product-level trends, outlet characteristics, customer ratings, and the factors influencing overall business performance**.

---

## 📌 Key KPIs

The dashboard provides an overview of important business metrics, including:

* **Total Sales**
* **Average Sales**
* **Average Rating**
* **Number of Items**

These KPIs provide a quick snapshot of the overall business performance.

---

## 📈 Dashboard Analysis

### 1. Outlet Size Analysis

The dashboard analyzes sales distribution across different outlet sizes to identify which outlet segments contribute most to overall sales.

### 2. Outlet Location Analysis

Sales are compared across different outlet location types to understand geographical/business-location performance.

### 3. Outlet Establishment Analysis

An area chart shows sales trends based on the **outlet establishment year**, helping identify changes in business performance over time.

### 4. Fat Content Analysis

The dashboard analyzes sales based on **item fat content**, allowing comparison between different product categories.

### 5. Fat Content by Outlet

Sales are further segmented by both **fat content and outlet location type** to identify patterns across outlet segments.

### 6. Item Type Analysis

The dashboard compares **total sales across different item types**, helping identify high-performing and low-performing product categories.

### 7. Outlet Type Performance

A detailed matrix provides a comparison of outlet types using metrics such as:

* Total Sales
* Number of Items
* Average Sales
* Average Rating

---

## 🎛️ Interactive Features

The dashboard includes interactive filters/slicers that allow users to explore the data dynamically.

Users can filter the analysis by:

* **Outlet Location Type**
* **Item Type**
* **Outlet Size**

A metric-selection parameter is also incorporated to allow different measures to be analyzed interactively.

---

## 🛠️ Tools & Technologies

| Tool              | Purpose                               |
| ----------------- | ------------------------------------- |
| **Power BI**      | Dashboard development & visualization |
| **Power Query**   | Data cleaning and transformation      |
| **DAX**           | Measures and KPI calculations         |
| **Data Modeling** | Structuring data for analysis         |
| **Excel/CSV**     | Data source                           |

---

## 🧮 Key DAX Measures

Examples of the measures used in the dashboard include:

```DAX
Total Sales = SUM(Table1[Sales])

Average Sales = AVERAGE(Table1[Sales])

Average Rating = AVERAGE(Table1[Rating])

No. of Items = DISTINCTCOUNT(Table1[Item Type])
```

These measures are used to create KPIs and dynamic visualizations throughout the dashboard.

---

## 💡 Key Insights

The dashboard can be used to identify:

* Which **item types** contribute the most to total sales.
* Which **outlet sizes** generate higher sales.
* How sales vary across different **outlet location types**.
* How product **fat content** is associated with sales.
* How sales performance has changed based on **outlet establishment year**.
* Which outlet types perform better across sales, item count, and customer ratings.

---

## 📷 Dashboard Preview

<img width="1286" height="699" alt="blinkit_dashboard" src="https://github.com/user-attachments/assets/58119a53-eeac-4606-921f-cd904ecfc3ad" />


---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `Blinkit_Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. If required, update the dataset/file path.
4. Refresh the data.
5. Use the available slicers and interactive visuals to explore the dashboard.

---

## 📂 Project Files

```text
├── Blinkit_Dashboard.pbix
├── Excel_Dataset file/
├── Dasboard_image/
└── README.md
```

---

## 👩‍💻 Author

**Jasleen Kaur**

Aspiring **Data Analyst** with a background in Computer Applications and a focus on data visualization, business intelligence, and analytical problem-solving.


