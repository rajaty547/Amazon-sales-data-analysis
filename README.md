# Amazon Sales Data Analysis

A data analytics project that explores Amazon-style sales records using **Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook, and Power BI**. The project includes exploratory data analysis (EDA), business-focused questions, visualizations, a Power BI report file, and a published interactive web dashboard.

## 🔗 Project Links

- **[Open the Live Interactive Dashboard](https://rajaty547.github.io/Amazon-sales-data-analysis/)**
- **[View the GitHub Repository](https://github.com/rajaty547/Amazon-sales-data-analysis)**

## 📌 Project Overview

The goal of this project is to analyze sales performance across regions, countries, item types, sales channels, and order priorities. It examines revenue, costs, profit, units sold, order processing time, and patterns over time to support business-oriented analysis.

The repository contains the original CSV dataset, a Python notebook and its HTML export, a PDF project document, and a Power BI `.pbix` file.

## 📁 Project Files

| File | Description |
|---|---|
| `Amazon Sales data.csv` | Source dataset used for the analysis |
| `Analyzing Amazon Sales data.ipynb` | Jupyter Notebook containing data inspection, cleaning demonstrations, analysis, and charts |
| `Project 1_Analyzing Amazon Sales data.pdf` | PDF project document |
| `index.html` | Published interactive web dashboard |
| `README.md` | Project documentation |

## 📊 Dataset at a Glance

The CSV contains **100 records and 14 columns**, with order dates ranging from **May 2010 to May 2017**. The dataset has no missing values in its original form.

Key fields include:

- **Order details:** `Order ID`, `Order Date`, `Ship Date`, `Order Priority`
- **Market details:** `Region`, `Country`, `Sales Channel`
- **Product details:** `Item Type`
- **Sales metrics:** `Units Sold`, `Unit Price`, `Unit Cost`
- **Financial metrics:** `Total Revenue`, `Total Cost`, `Total Profit`

The records cover 7 regions, 76 countries, 12 item types, and both online and offline sales channels.

## 🧰 Tools & Technologies

- **Python** — analysis and data manipulation
- **Pandas** — loading, cleaning, grouping, and summarizing data
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical charts
- **Jupyter Notebook** — analysis workflow
- **Power BI** — report file (`.pbix`)
- **HTML, CSS, JavaScript** — published web dashboard
- **GitHub Pages** — dashboard hosting

## 🔍 Analysis Questions

The notebook explores questions such as:

1. Which regions generate the highest total sales revenue?
2. What are the average unit prices and unit costs for each item type?
3. Which country has the highest total profit?
4. How are order priorities distributed across online and offline sales channels?
5. What is the average time between order and shipment for each sales channel and country?
6. Which item types have the highest and lowest total revenue?
7. How does order priority vary by region and item type?
8. What is the correlation between unit price and total profit?
9. Are there monthly revenue patterns in the data?
10. How do units sold and revenue vary across countries?
11. Are there outliers in the total cost distribution?
12. Is there a relationship between units sold and total profit?

## 📈 Analysis & Visualizations

The Python notebook uses grouped summaries and visualizations, including:

- Revenue by region and country
- Average unit price and unit cost by item type
- Total profit by country and item type
- Order priority distribution by sales channel and region
- Average order-to-shipment duration
- Monthly revenue patterns
- Units sold by country
- Unit price distribution by item type
- Total cost outlier exploration using the interquartile range (IQR)
- Correlation checks between selected sales metrics

## 💡 Key Metrics

The dataset provides the following measures:

| Metric | Meaning |
|---|---|
| Units Sold | Total quantity sold |
| Total Revenue | Revenue recorded for the order |
| Total Cost | Cost recorded for the order |
| Total Profit | Profit recorded for the order |
| Order Processing Time | Difference between `Ship Date` and `Order Date` |
| Profit Margin | Total profit divided by total revenue |

For reference, summing the supplied CSV gives **512,871 units sold**, **137,348,768.31 total revenue**, **93,180,569.91 total cost**, and **44,168,198.40 total profit**. These are totals for the provided 100 records; check the dataset's original currency/context before using them in formal reporting.

## 🚀 Run the Python Analysis

1. Clone the repository:

   ```bash
   git clone https://github.com/rajaty547/Amazon-sales-data-analysis.git
   cd Amazon-sales-data-analysis
   ```

2. Install the Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Analyzing Amazon Sales data.ipynb` and run the cells.

Make sure `Amazon Sales data.csv` is in the same working directory as the notebook.

## 📊 Open the Power BI Report

1. Download or clone this repository.
2. Open `Amazon Sales data.pbix` using Microsoft Power BI Desktop.
3. If prompted, verify the data source path and update it to the location of `Amazon Sales data.csv`.

The `.pbix` file is the Power BI report artifact; use Power BI Desktop to inspect or modify it.

## 🌐 Live Web Dashboard

The interactive HTML dashboard is published with GitHub Pages:

**[https://rajaty547.github.io/Amazon-sales-data-analysis/](https://rajaty547.github.io/Amazon-sales-data-analysis/)**

The live dashboard is separate from the downloadable Power BI `.pbix` file. The live link lets visitors view the web version in a browser, while the `.pbix` file can be opened in Power BI Desktop.

## 🎯 Skills Demonstrated

- Data loading, inspection, and cleaning workflow
- Exploratory data analysis using Pandas
- Aggregation and grouping for business questions
- Data visualization with Matplotlib and Seaborn
- Sales and profitability metric interpretation
- Date-based analysis and order-to-shipment duration
- Working with Jupyter Notebook and Power BI report files
- Publishing a dashboard using GitHub Pages

## 👤 Author

**Rajat Yadav**

- **GitHub:** [@rajaty547](https://github.com/rajaty547)
- **Repository:** [Amazon Sales Data Analysis](https://github.com/rajaty547/Amazon-sales-data-analysis)
- **Live Dashboard:** [View Interactive Dashboard](https://rajaty547.github.io/Amazon-sales-data-analysis/)

---

If you find this project useful, feel free to ⭐ the repository.
