# 🛒 Blinkit Sales Analysis — Power BI Dashboard

An interactive Power BI dashboard analysing sales performance, customer ratings and inventory distribution for **Blinkit (India's Last Minute App)** using grocery sales data.

![Blinkit Dashboard](images/dashboard.png)

## 📌 Business Requirement

Conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction and inventory distribution, and identify opportunities for optimisation using KPIs and visualisations in Power BI.

## 📊 KPIs

| KPI | Description |
|---|---|
| **Total Sales** | Overall revenue generated from all items sold |
| **Average Sales** | Average revenue per sale |
| **Number of Items** | Total count of items sold |
| **Average Rating** | Average customer rating for items sold |

## 📈 Charts & Analysis

1. **Total Sales by Fat Content** – impact of fat content on sales (donut chart)
2. **Total Sales by Item Type** – top and bottom performing categories (bar chart)
3. **Fat Content by Outlet** – sales across outlet tiers segmented by fat content
4. **Total Sales by Outlet Establishment Year** – how outlet age influences sales (area chart)
5. **% of Sales by Outlet Size** – correlation between outlet size and sales (donut chart)
6. **Sales by Outlet Location** – Tier 1 / Tier 2 / Tier 3 distribution
7. **All Metrics by Outlet Type** – Total Sales, Avg Sales, Items, Rating and Item Visibility in one table

The dashboard also has **slicers** (Outlet Location Type, Outlet Size, Item Type) and a **metric selector** that switches the charts between Total Sales, Avg Sales, Number of Items and Average Rating.

## 🗂️ Dataset

`BlinkIT_Grocery_Data.xlsx` — 8,523 rows, 12 columns:

`Item Fat Content`, `Item Identifier`, `Item Type`, `Outlet Establishment Year`, `Outlet Identifier`, `Outlet Location Type`, `Outlet Size`, `Outlet Type`, `Item Visibility`, `Item Weight`, `Sales`, `Rating`

### Data cleaning
`Item Fat Content` contained inconsistent labels (`LF`, `low fat`, `reg`). These were standardised to **Low Fat** and **Regular**.

## 🛠️ Tools Used

- Power BI Desktop (data modelling, DAX measures, visuals)
- Excel (source data)
- PowerPoint (requirements documentation)

## 📁 Repository Structure

```
├── BlinkIT_Grocery_Data.xlsx     # Source dataset
├── Blinkit_Analysis.pptx         # Business requirements
├── Blinkit.pbix                  # Power BI report (add your file here)
├── images/
│   └── dashboard.png             # Dashboard screenshot
└── README.md
```

## 🚀 How to Use

1. Clone the repo: `git clone https://github.com/<your-username>/blinkit-powerbi-analysis.git`
2. Open the `.pbix` file in Power BI Desktop.
3. If prompted, point the data source to `BlinkIT_Grocery_Data.xlsx`.
4. Use the slicers and metric tabs to explore.

## 💡 Key Insights

> Fill these in from your dashboard, for example:
- Which item types drive the most revenue (e.g. Fruits & Vegetables, Snack Foods, Household)
- Which outlet tier contributes the most sales
- How outlet size splits total sales
- Whether Low Fat or Regular items sell more

## 👤 Author

**Your Name** — [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

⭐ If you found this useful, give the repo a star!
