# 🍕 Pizza Sales Dashboard

An interactive, multi-page Power BI dashboard that analyzes a full year of pizza sales. It tracks revenue, orders, best and worst performing pizzas, category and size performance, and hourly sales patterns, so a restaurant owner can see what sells, when it sells, and where the money comes from.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
| Total Revenue |$817.86K|
| Total Orders |21,350|
| Total Pizzas Sold |49,574|
| Average Order Value (AOV) |$38.31|
| Avg. Pizzas per Order |2.32|
| Highest Order Value |$444.20|

---

## 🗂️ Dashboard Pages

### 1. Sales Overview
- Total pizzas sold and total revenue KPI cards
- **Monthly revenue trend** (bar chart): revenue stays steady at roughly $64K–$73K per month, with July the strongest month
- **Revenue by day type**: weekdays generate about 72.8% of revenue, weekends about 27.2%
- **Revenue by pizza size**: Large leads with about 45.9%, followed by Medium (30.5%) and Small (21.8%); XL and XXL are minor contributors
- Slicers: Pizza Size, Pizza Name, Pizza Category

### 2. Hourly Sales Analysis
- **Total orders by hour** and **total revenue by hour** (line charts)
- Clear lunch peak (12 PM–1 PM) and a second evening peak (5 PM–7 PM)
- Slicers: Month, Category, Hour Label, Pizza Size

### 3. Revenue Trend Analysis
- KPI cards: Total Orders, Total Revenue, AOV, Total Pizza Sold, Avg. Pizzas per Order, Highest Order Value
- **Revenue by category** (donut): Classic, Supreme, Chicken and Veggie each contribute close to a quarter of revenue
- **Pizzas sold by category** (bar): Classic sells the most units, followed by Supreme, Veggie and Chicken
- Slicers: Month, Category


### 4. Product Performance
- **Top 10 pizzas by revenue**: led by The Thai Chicken Pizza, The Barbecue Chicken Pizza and The California Chicken Pizza
- **Top 10 pizzas by quantity sold**: led by The Classic Deluxe Pizza, The Barbecue Chicken Pizza and The Hawaiian Pizza
- **Bottom 5 pizzas by revenue**: The Brie Carre Pizza, The Green Garden Pizza, The Spinach Supreme Pizza, and others
- Category-wise and size-wise revenue tables
- Detailed **summary table** with total orders, pizzas sold, revenue, AOV and month-over-month (MoM) growth
- Month slicer
---

## 🔍 Key Insights

- **Lunch is the busiest time**: 12 PM brings the most orders and revenue (about $112K), followed by 1 PM, with a second rush around 6 PM.
- **Large pizzas drive the business**: Large pizzas bring in the largest share of revenue (about 46%).
- **Weekdays dominate**: Weekdays account for roughly 73% of total revenue.
- **Categories are well balanced**: Classic is the top revenue category, but all four categories are within a narrow range.
- **Chicken pizzas win on revenue**: They fill the top spots for revenue even though Classic sells more units.
- **Sales are steady all year**: Monthly revenue is consistent, peaking in July and dipping slightly in September and October.

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop**: report design and visualization
- **DAX**: measures for revenue, AOV, orders, MoM growth, etc.
- **Power Query**: data cleaning and transformation
- **Data modeling**: date, category and size relationships

---

## 📁 Repository Structure

```
├── Pizza_Sales_Dashboard.pbix     # Power BI dashboard file
├── data/                          # Source dataset (CSV / Excel)
├── images/                        # Dashboard screenshots
│   ├── 01_Sales Overview.png
│   ├── 02_Hourly Analysis.png
│   ├── 03_Revenue Trend Analysis.png
│   └── 04_Product Performance.png
└── README.md
```

> Update the file names above to match your repository.

---

## 🖼️ Screenshots

### 1️⃣ Sales Overview
![Sales Overview](01_Sales%20Overview.png)

- Total pizzas sold (**49,574**) and total revenue (**$817.86K**)
- **Monthly revenue trend**: revenue stays between about $64K and $73K each month, with July the strongest month and September and October the weakest
- **Revenue by day type**: weekdays bring in about 72.8% ($595.47K) and weekends about 27.2% ($222.38K)
- **Revenue by pizza size**: Large 45.9%, Medium 30.5%, Small 21.8%, XL 1.7%, XXL very small
- **Slicers**: Pizza Size, Pizza Name, Pizza Category

---

### 2️⃣ Pizza Performance
![Pizza Performance](02_Hourly%20Sales%20Analysis.png)

- **Top 10 pizzas by revenue** (total $364,285.45): led by The Thai Chicken Pizza ($43,434), The Barbecue Chicken Pizza ($42,768) and The California Chicken Pizza ($41,409)
- **Top 10 pizzas by quantity sold** (total 21,613): led by The Classic Deluxe Pizza (2,453), The Barbecue Chicken Pizza (2,432) and The Hawaiian Pizza (2,422)
- **Bottom 5 pizzas by revenue**: The Brie Carre, Green Garden, Spinach Supreme, Mediterranean and Spinach Pesto pizzas
- **Category-wise revenue**: Classic $220K, Supreme $208K, Chicken $196K, Veggie $194K
- **Size-wise revenue**: L $375K, M $249K, S $178K, XL $14K, XXL $1K
- **Summary table**: orders, pizzas sold, revenue, AOV and month-over-month (MoM) growth for each pizza and size
- **Slicer**: Month

---

### 3️⃣ Category Analysis
![Category Analysis](03_Revenue%20Trend%20Analysis.png)

- **KPI cards**: Total Orders, Total Revenue, AOV, Total Pizza Sold, Avg. Pizzas per Order, Highest Order Value
- **Revenue by category** (donut): Classic 26.9%, Supreme 25.5%, Chicken 24.0%, Veggie 23.7%
- **Pizzas sold by category** (bar): Classic 14.9K, Supreme 12.0K, Veggie 11.6K, Chicken 11.1K
- **Slicers**: Month, Category

---

### 4️⃣ Hourly Sales Analysis
![Hourly Sales Analysis](04_Product%20Performance.png)

- **Total orders by hour**: the busiest hours are 12 PM (2,520 orders), 1 PM (2,455) and 6 PM (2,399)
- **Total revenue by hour**: the lunch peak reaches about $112K at 12 PM, with a second peak of about $89K at 6 PM
- Almost no orders before 10 AM and after 10 PM
- **Slicers**: Month, Category, Hour Label, Pizza Size

---

## 📌 Possible Improvements

- Add year-over-year comparison with multi-year data
- Add forecasting for monthly revenue
- Add a profit-margin view using ingredient cost data
- Publish to Power BI Service for live sharing

---

## 👤 Author

Md. Asraf Ibney Ajad

GitHub: https://github.com/itsasraf
LinkedIn: www.linkedin.com/in/md-asraf-ibney-ajad-7719522a0


