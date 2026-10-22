# Amazon Sales Analysis Dashboard

An interactive sales analytics project that explores revenue, costs, profitability, sales channels, regions, and product performance across 100 order records.

## 🔴 Live Dashboard

**[View the Interactive Amazon Sales Dashboard](https://rajaty547.github.io/Amazon-sales-data-analysis/)**

Explore the dashboard online. Use the region, sales channel, and year filters to analyze different subsets of the data.

## 📌 Project Overview

The **Amazon Sales Analysis Dashboard** transforms sales records into an interactive visual report. It helps users explore key performance indicators (KPIs), compare revenue across regions and channels, examine product profitability, and review order-level records.

The dashboard was built with HTML, CSS, JavaScript, and Chart.js and is published using GitHub Pages.

## ✨ Dashboard Features

- **KPI cards:** Units sold, total revenue, total cost, total profit, profit margin, and number of orders.
- **Interactive filters:** Filter the dashboard by region, sales channel, and year.
- **Regional performance:** Compare revenue across sales regions.
- **Sales channel analysis:** Explore revenue distribution across online and offline channels.
- **Product profitability:** Compare profit, revenue, cost, and profit margin by item type.
- **Sales trends:** Analyze units sold by year.
- **Country analysis:** Identify the top 10 countries by units sold in the selected view.
- **Order priority analysis:** Review order counts by priority and sales channel.
- **Data tables:** Explore item-level summaries and filtered order-level records.
- **Responsive design:** Dashboard layout adapts to desktop and smaller screens.

## 📊 Key Performance Indicators

The dashboard calculates and displays:

| KPI | Description |
|---|---|
| Units Sold | Sum of units sold across the selected orders |
| Total Revenue | Sum of units sold multiplied by unit price |
| Total Cost | Sum of units sold multiplied by unit cost |
| Total Profit | Total revenue minus total cost |
| Profit Margin | Total profit divided by total revenue, expressed as a percentage |
| Orders | Number of order records matching the selected filters |

> **Note:** The figures shown in the dashboard are calculated from the data embedded in this project. Verify the original dataset's currency and business context before using the values in formal reporting.

## 🛠️ Tools & Technologies

- **HTML5** — dashboard structure
- **CSS3** — styling and responsive layout
- **JavaScript** — filtering, data aggregation, and interactions
- **Chart.js** — interactive charts and visualizations
- **GitHub** — source control and project repository
- **GitHub Pages** — dashboard hosting

## 📈 Visualizations

The dashboard includes these report sections:

### 1. Overview
- Revenue by region
- Revenue mix by sales channel
- Profit by item type
- Top 10 countries by units sold

### 2. Sales Trends
- Units sold by year
- Cost versus profit
- Revenue by item type
- Orders by priority and sales channel

### 3. Product Analysis
- Cost by item type
- Profit margin by item type
- Item type performance table with units, revenue, cost, profit, and margin

### 4. Data Table
- Filtered order-level records, including year, region, country, item type, sales channel, priority, units sold, revenue, cost, and profit

## 🗂️ Repository Contents

The repository includes the following project files:

- `index.html` — interactive dashboard published through GitHub Pages
- `Amazon Sales data.csv` — CSV dataset
- `Analyzing Amazon Sales data.ipynb` — Jupyter notebook for data analysis
- `Amazon Sales data_Python.pdf` — accompanying PDF document
- `README.md` — project documentation

## 🚀 Run the Dashboard Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/rajaty547/Amazon-sales-data-analysis.git
   ```

2. Open the project folder:

   ```bash
   cd Amazon-sales-data-analysis
   ```

3. Open `index.html` in a modern web browser.

The dashboard loads Chart.js from a CDN, so an internet connection is required for the charts to render.

## 🌐 Deployment

This dashboard is hosted using **GitHub Pages**.

- **Live dashboard:** https://rajaty547.github.io/Amazon-sales-data-analysis/
- **Source repository:** https://github.com/rajaty547/Amazon-sales-data-analysis/

To publish updates, commit changes to the `main` branch and confirm that GitHub Pages is configured to deploy from the repository root.

## 📚 Dataset Notes

The dashboard uses 100 order records embedded in the HTML file. The dashboard contains fields for region, country, item type, sales channel, order priority, year, units sold, unit price, and unit cost.

The dashboard derives revenue, cost, and profit from these fields. The embedded data covers the date range **February 2010 to May 2017**.

## 💡 Learning Outcomes

- Building an interactive dashboard with HTML, CSS, and JavaScript
- Creating charts with Chart.js
- Calculating and presenting business KPIs
- Grouping and filtering records for analysis
- Designing a responsive data visualization interface
- Publishing a static dashboard with GitHub Pages

## 👤 Author

**Rajat Yadav**

- GitHub: [@rajaty547](https://github.com/rajaty547)
- Project Repository: [Amazon Sales Data Analysis](https://github.com/rajaty547/Amazon-sales-data-analysis)
- Live Dashboard: [View Dashboard](https://rajaty547.github.io/Amazon-sales-data-analysis/)

---

If you find this project useful, consider giving the repository a ⭐.
