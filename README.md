# 🛒 Blinkit Sales Performance Dashboard (Power BI)

A comprehensive analytics dashboard analyzing **Blinkit’s sales performance**, **customer satisfaction**, and **inventory distribution** using Power BI. This project applies essential data analytics techniques—including Key Performance Indicators (KPIs), DAX measures, and interactive visualizations—to derive actionable business insights.

## 🚀 Project Objective

To analyze sales, ratings, and outlet performance to help stakeholders understand what drives sales, which products perform best, and which outlets need optimization.

## 🛠 Tools & Technologies

| Tool | Purpose |
| :--- | :--- |
| **Power BI Desktop** | Core development and visualization tool. |
| **Power Query (M Language)** | Data cleaning, transformation, and structure preparation. |
| **DAX (Data Analysis Expressions)** | Creating custom measures, calculated columns, and KPIs. |
| **Excel** | Source data management. |

---

## 📊 Key Performance Indicators (KPIs)

The following metrics are tracked and analyzed in the dashboard:

* **Total Sales**
* **Average Sales**
* **Number of Items Sold**
* **Average Rating**

## 📈 Dashboard Insights & Visualizations

The dashboard features several key analyses to provide deep insights:

### 1. Total Sales by Fat Content

* Compares how **Low Fat** vs **Regular Fat** products perform.
* **KPIs:** Total Sales, Avg Sales, Ratings, Count of Items.

### 2. Total Sales by Item Type

* Identifies top-performing product categories (e.g., snacks, dairy).
* **Additional insights:** which categories have better ratings or visibility.

### 3. Fat Content by Outlet for Total Sales

* Checks which outlets sell more low-fat or regular-fat items.
* **Supports:** Inventory and replenishment decisions.

### 4. Total Sales by Outlet Establishment Year

* Analyzes if older outlets generate more sales compared to newer ones.

### 5. Percentage of Sales by Outlet Size

* Understand correlation between size (**Small/Medium/High**) and revenue.

### 6. Sales by Outlet Location Type

* Shows geographical impact on sales patterns (**Tier 1 / Tier 2 / Tier 3**).

### 7. All Metrics by Outlet Type

* Comprehensive view comparing **Total Sales, Avg Sales, Items, and Ratings** across different Outlet Types (e.g., Supermarket Type 1 vs Type 2 vs Grocery Store).

---

## 🧠 Dataset Columns Used

| Column | Description |
| :--- | :--- |
| `Item Fat Content` | Fat category of item |
| `Item Identifier` | Unique item code |
| `Item Type` | Product category |
| `Outlet Establishment Year` | Year outlet started |
| `Outlet Identifier` | Unique store code |
| `Outlet Location Type` | Tier-1, Tier-2, Tier-3 |
| `Outlet Size` | Small, Medium, Large |
| `Outlet Type` | Grocery, Supermarket Type 1/2/3 |
| `Item Visibility` | Shelf visibility score |
| `Item Weight` | Weight of item |
| `Total Sales` | Revenue from the item |
| `Rating` | Customer rating |

---

## 📸 Dashboard Preview

![Dashboard Preview](images/blinkit_dashboard.png)

## 📂 Files Included

* `Blinkit_Dashboard.pbix`: The Power BI project file.
* `images/`: Folder containing screenshots.
* `README.md`: This file.

## 📥 How to Use

1.  Download the `.pbix` file.
2.  Open it in **Power BI Desktop**.
3.  Interact with the slicers, filters, and visuals to explore the data model.
