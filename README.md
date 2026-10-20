# 🍕 Pizza Sales Dashboard

An interactive Power BI dashboard that analyzes pizza sales across orders, hours, months, categories, sizes and individual products. It helps answer questions like: *When are sales highest? Which pizzas drive revenue? Which sizes and categories perform best?*

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Orders | 21,350 |
| Total Pizzas Sold | 49,574 |
| Total Revenue | $817.86K |
| Average Order Value (AOV) | $38.31 |
| Avg. Pizzas Sold per Order | 2.32 |
| Highest Order Value | $444.20 |

---

## 📑 Dashboard Pages

The report has four pages, in this order:

### 01 – Sales Overview
![Sales Overview](01_Sales_Overview.png)

A high-level summary of business performance.
- KPI cards: Total Orders, Total Revenue, AOV, Total Pizza Sold, Avg. Pizzas Sold per Order, Highest Order Value
- **Total Revenue by Category** (donut chart)
- **Total Pizza Sold by Category** (bar chart)
- Slicers: Month, Category

**Insights**
- Classic is the top category by revenue (~$220.05K, 26.91%), followed by Supreme (~$208.2K), Chicken (~$195.92K) and Veggie (~$193.69K).
- Classic also sells the most pizzas (~14.9K).

### 02 – Hourly Sales Analysis
![Hourly Sales Analysis](02_Hourly_Sales_Analysis.png)

Shows how orders and revenue change through the day.
- KPI cards: Orders by Hour, Total Pizza Sold, Sales by Hour, AOV
- **Total Orders by Hour** (line chart)
- **Total Revenue by Hour** (line chart)
- Slicers: Month Name, Category, Hour Label, Pizza Size

**Insights**
- The lunch peak is the busiest period: 12 PM (2,520 orders, ~$112K) and 1 PM (2,455 orders, ~$106K).
- A second peak appears in the evening around 5–6 PM (~2,400 orders at 6 PM, ~$89K).
- Sales are very low at 9–10 AM and after 10 PM.

### 03 – Revenue Trend Analysis
![Revenue Trend Analysis](03_Revenue_Trend_Analysis.png)

Tracks revenue over time and by day type and size.
- **Monthly Revenue Trend** (column chart)
- **Total Revenue by Day Type** (weekday vs weekend donut)
- **Total Revenue by Pizza Size** (donut)
- Slicers: Pizza Size, Pizza Name, Pizza Category

**Insights**
- Monthly revenue stays fairly steady at ~$64K–$73K, with July the highest (~$73K) and Sep/Oct the lowest (~$64K).
- Weekdays generate ~72.8% of revenue and weekends ~27.2%.
- Large (L) pizzas contribute the most revenue (~45.9%), followed by Medium (~30.5%) and Small (~21.8%). XL and XXL are minimal.

### 04 – Product Performance
![Product Performance](04_Product_Performance.png)

Compares individual pizzas, categories and sizes.
- **Top 10 Pizzas by Revenue**
- **Top 10 Pizzas by Quantity Sold**
- **Bottom 5 Pizzas by Revenue**
- **Category-wise Revenue** and **Pizza Size-wise Revenue** tables
- **Summary Table** with Category, Size, Total Orders, Total Pizza Sold, Total Revenue, AOV and MoM Revenue Growth
- Slicer: Month

**Insights**
- The Thai Chicken Pizza leads in revenue (~$43.4K), followed by The Barbecue Chicken Pizza and The California Chicken Pizza.
- The Classic Deluxe Pizza sells the most units (2,453).
- The Brie Carre Pizza has the lowest revenue (~$11.6K), and the bottom 5 are mostly Veggie/Supreme pizzas.

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop**: data modeling, DAX measures, visuals, slicers
- Data cleaning and transformation (Power Query)
- KPI cards, line charts, column charts, donut charts, bar charts, tables
- Interactive filtering with slicers and dropdowns

---

## 📁 Project Structure

```
├── Dashboard_Pizza_Dataset.pbix
├── 01_Sales_Overview.png
├── 02_Hourly_Sales_Analysis.png
├── 03_Revenue_Trend_Analysis.png
├── 04_Product_Performance.png
└── README.md
```

---

## ▶️ How to Use

1. Download `Dashboard_Pizza_Dataset.pbix`.
2. Open it in **Power BI Desktop**.
3. Use the slicers (month, category, size, hour, pizza name) to explore the data.
4. Switch between the four pages using the page tabs at the bottom.

---

## 💡 Business Takeaways

- Staff and prepare for the **12–1 PM** and **5–6 PM** rushes.
- Focus promotions on **weekends**, which contribute much less revenue than weekdays.
- **Large** and **Classic** pizzas are the core revenue drivers.
- Review or rework the bottom-performing pizzas, and consider promoting XL/XXL sizes, which sell poorly.

---

## 👤 Author

**[Your Name]**
[LinkedIn](#) | [GitHub](#) | [Email](#)
