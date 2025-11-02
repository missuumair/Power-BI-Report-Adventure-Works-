# 📊 Power BI Report - AdventureWorks Analysis

<div align="center">

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-E97627?style=for-the-badge&logo=microsoft&logoColor=white)


**An interactive business intelligence solution for comprehensive sales, profitability, and customer analytics**

[View Demo](#-dashboard-preview) · [Report Bug](https://github.com/missuumair/Power-BI-Report-Adventure-Works-/issues) · [Request Feature](https://github.com/missuumair/Power-BI-Report-Adventure-Works-/issues)

</div>

---

## 🎯 Project Overview

This Power BI report delivers an **end-to-end business intelligence analysis** using the **AdventureWorks dataset**. It provides interactive insights across multiple business dimensions:

- 📈 **Sales Performance** - $24.9M revenue with comprehensive trend analysis
- 💰 **Profitability Tracking** - $10.5M profit monitoring across products and regions
- 🌍 **Geographic Intelligence** - Interactive map visualization across global territories
- 👥 **Customer Analytics** - 10.5K unique customers with segmentation and behavior patterns
- 📦 **Product Intelligence** - Deep-dive analysis of 25.2K orders across categories
- 🎯 **Target Management** - Performance vs. target tracking with KPI monitoring

The solution empowers business users to make **data-driven decisions** through intuitive visualizations and real-time insights.

---

## 🗂️ Dataset Information

Built on **Microsoft's AdventureWorks sample database**, the dataset includes:

| Data Category | Description |
|--------------|-------------|
| 💵 **Sales Data** | Orders, revenue ($24.9M), profit ($10.5M), and transaction history |
| 👤 **Customer Data** | 10.5K unique customers with demographics, regions, and segmentation |
| 📦 **Product Data** | 25.2K orders across categories like Accessories, Bikes, and Clothing |
| 🌍 **Geographic Data** | Global coverage - United States, Canada, Australia, UK, France, Germany |
| 📅 **Time Intelligence** | Monthly, quarterly, and yearly trend tracking (2020-2022) |

**Data Transformation:**
- Cleaned and transformed using **Power Query**
- Enhanced with custom **DAX measures** for advanced analytics
- Implemented **star schema** data modeling for optimal performance
- 0.0 return rate monitoring for quality assurance

---

## 📊 Key Report Pages & Insights

### 1️⃣ Executive Dashboard (Page 1)
**Key Metrics:**
- 💰 **Total Revenue**: $24.9M
- 📈 **Total Profit**: $10.5M  
- 📦 **Total Orders**: 25.2K
- 🔄 **Return Rate**: 0.0

**Visualizations:**
- **Revenue Trending**: Time series from Jan 2020 to Jan 2022 with confidence bands
- **Orders by Category**: 
  - Accessories: 17.0K orders
  - Bikes: 13.9K orders
  - Clothing: 7.0K orders
- **Top 10 Products Table**: Detailed analysis with orders, revenue, and return percentage
  - Top Product: AWC Logo Cap (2062 orders, $35,882)
  - Featured products: Mountain Bottle Cage, Fender Set, Tire Tubes, Patches
- **Monthly Performance Cards**:
  - Monthly Revenue: $1.83M (+3.31% vs prev month)
  - Monthly Orders: 2,146 (-0.86% vs prev month)
  - Monthly Returns: 166 (+1.78% vs prev month)
- **Product Type Highlights**:
  - Most Ordered: Tires and Tubes
  - Most Returned: Shorts

### 2️⃣ Geographic Analysis (Page 2)
- 🗺️ **Interactive World Map**: Bubble visualization showing regional performance
- **Regional Coverage**:
  - 🇺🇸 United States (Largest market)
  - 🇨🇦 Canada
  - 🇦🇺 Australia  
  - 🇬🇧 United Kingdom
  - 🇫🇷 France
  - 🇩🇪 Germany
- **Territory Filters**: Select all, Europe, North America, Pacific
- 🔍 Drill-through capabilities for regional deep-dive
- Territory-based performance comparison

### 3️⃣ Product Details (Page 3)
**Interactive Analysis:**
- **Selected Product Focus**: Patch Kit/8 Patches
- **Performance Gauges**:
  - Monthly Orders vs Target: 265 / 530
  - Monthly Revenue vs Target: $1,225 / $1,494
  - Monthly Profit vs Target: $767 / $935
- **Price Adjustment Simulator**: 0.20 adjustment slider
- **Dual-Line Charts**:
  - Adjusted Profit vs Total Profit comparison
  - Historical trend from Jul 2021 to May 2022
- **Product Metric Selection**:
  - ⭕ Orders
  - ⭕ Revenue
  - 🔵 Profit (Selected)
  - ⭕ Returns
  - ⭕ Return %
- **Time Series Analysis**: Monthly granularity with area charts

### 4️⃣ Customer Intelligence (Page 4)
**Customer Overview:**
- 👥 **Total Unique Customers**: 10.5K
- 💵 **Revenue per Customer**: $0.1

**Customer Segmentation:**
- **Order by Income Level**:
  - High: 1.3K customers
  - Average: 9.5K customers
  - Low: 4.8K customers
  
- **Orders by Occupation**:
  - Management: 2.0K
  - Professional: 3.8K
  - Skilled Manual: 2.7K

**Top 100 Customers Table:**
- Customer ranking by revenue
- Full name, order count, and revenue metrics
- Top Customer: Mr. Jordan Turner (5 orders, $52,842)
- Featured customers: Mrs. Lacey Zheng, Mr. Marco Lopez, Mrs. Ariana Gray
- Total orders tracked: 730 orders, $1,39,375 revenue

**Customer Detail Card:**
- Drill-through capability showing individual customer performance
- Selected Customer: Mr. Jordan Turner
- Orders: 88
- Revenue: 62.8K
- Contextual information: "Customer with Hight Revenue Mr.Jordhan Turner , at 6.8k"

**Trending Analysis:**
- Revenue growth from Jan 2022 to Jun 2022
- Customer acquisition and retention metrics

---

## 🧰 Tools & Technologies

```
Power BI Desktop    → Main reporting and visualization platform
Power Query         → Data extraction, transformation, and loading (ETL)
DAX                 → Advanced calculations and measures
SQL Server          → Source database (AdventureWorks)
Excel               → Supplementary data source
```

### Key Features Implemented:
- ⚡ Dynamic filtering and slicers across all pages
- 🔄 Drill-through functionality for detailed analysis
- 📱 Mobile-responsive layout with 9 optimized pages
- 🎨 Professional dark theme with consistent branding
- 📊 Advanced DAX measures including YoY, MoM comparisons
- 🔗 Relationship modeling with star schema architecture
- 🎯 Interactive gauge charts for target tracking
- 🗺️ Bing Maps integration for geographic visualization
- 📈 Time intelligence with rolling calculations
- 💡 Tooltip integration for enhanced user experience

---

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- AdventureWorks database access OR sample Excel files

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/missuumair/Power-BI-Report-Adventure-Works-.git
   cd Power-BI-Report-Adventure-Works-
   ```

2. **Open the Power BI file**
   ```
   Open "AdventureWorks_Report.pbix" in Power BI Desktop
   ```

3. **Configure data source** (if needed)
   - Go to Transform Data → Data Source Settings
   - Update connection strings to your AdventureWorks database
   - Refresh the data

4. **Explore the report**
   - Navigate through 9 interactive pages
   - Use slicers to filter by region, product, or time period
   - Test drill-through functionality on customer and product details
   - Interact with the price adjustment simulator

---

## 📸 Dashboard Preview

<div align="center">

### 📊 Executive Dashboard
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d3e7c615-c2f1-40c4-b0f4-f9175e8befc0" />
*Comprehensive overview with $24.9M revenue, $10.5M profit, and 25.2K orders tracking*

---

### 🗺️ Geographic Analysis
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cad04385-767a-41c0-bd2a-76f9961a9ec7" />
*Interactive world map showing performance across 6 territories: US, Canada, Australia, UK, France, and Germany*

---

### 📦 Product Details & Analysis
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/670729d3-ed34-4a7e-852b-3920af945c8e" />
*Drill-through product analysis with target vs actual performance, price adjustment simulator, and trend analysis*

---

### 👥 Customer Intelligence
img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/65587aa8-c10b-4fa3-a265-0d9a86e66c7e" />
*10.5K unique customers with segmentation by income level, occupation, and top 100 customer leaderboard*

### 👥 Key Influencer
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/022b8498-9a94-4d2b-ae58-68b75acb1711" />

</div>

> **Note:** Screenshots showcase actual report pages. Add your own screenshots to the `/images` folder in your repository.

---

## 📐 Data Model

The report uses a **star schema** architecture with the following structure:

### 📊 Fact Tables
- **Sales Data** - Core transaction data with 25.2K orders, $24.9M revenue
- **Returns Data** - Product return tracking (0.0% return rate)
- **Measure Table** - Centralized DAX measures and calculations
- **Measure Selector** - Dynamic measure selection for interactive analysis

- <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7909e488-2be7-4688-bb85-802f2fc20b56" />

### 🔍 Dimension Tables
| Dimension | Description | Key Attributes |
|-----------|-------------|----------------|
| **Calendar Lookup** | Date/time intelligence | Day, Month, Year, Start of Month slicer |
| **Customer Lookup** | Customer demographics | 10.5K unique customers, Name, Income Level |
| **Territory Lookup** | Geographic territories | 6 regions: US, Canada, Australia, UK, France, Germany |
| **Product Lookup** | Product catalog | Categories, Subcategories, Product names |
| **Product Subcategories Lookup** | Product hierarchy | Accessories, Bikes, Clothing subcategories |
| **Product Categories Lookup** | Top-level categories | Main product groupings |
| **Customer Priority** | Customer segmentation | High (1.3K), Average (9.5K), Low (4.8K) |
| **Customer Metric** | Customer KPIs | Revenue per customer ($0.1) |
| **Price Adjustment (%)** | Pricing scenarios | 0.20 adjustment slider for simulation |
| **Product Metric Selection** | Product KPI toggle | Orders, Revenue, Profit, Returns, Return % |
| **Time Intelligence** | Advanced date calculations | YoY, MoM, rolling averages |

### 🔗 Relationship Structure
```
           ┌─────────────────────────────┐
           │      Sales Data (Fact)      │
           │   25.2K Orders | $24.9M     │
           └──────────────┬──────────────┘
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
   ┌────▼─────┐     ┌─────▼──────┐    ┌────▼────────┐
   │ Calendar │     │  Customer  │    │   Product   │
   │  Lookup  │     │   Lookup   │    │   Lookup    │
   │2020-2022 │     │   10.5K    │    │  Categories │
   └──────────┘     └──────┬─────┘    └─────┬───────┘
                           │                 │
                    ┌──────▼──────┐   ┌──────▼────────────┐
                    │  Territory  │   │  Subcategories    │
                    │   Lookup    │   │     Lookup        │
                    │  (6 regions)│   │ (Accessories,     │
                    └─────────────┘   │  Bikes, Clothing) │
                                      └───────────────────┘
```

**Key Features:**
- ⭐ Star schema for optimal query performance
- 🔄 One-to-many relationships throughout
- 🎯 Bidirectional filtering on select relationships
- 📊 Separate measures table for organized DAX code
- 🔗 15 total tables supporting 9 interactive report pages

---

## 🎓 Key DAX Measures

### Core Business Metrics
```dax
Total Revenue = 
SUM('Sales Data'[Revenue])
// Result: $24.9M

Total Profit = 
SUM('Sales Data'[Profit])
// Result: $10.5M

Total Orders = 
COUNT('Sales Data'[OrderNumber])
// Result: 25.2K

Return Rate = 
DIVIDE(
    CALCULATE(COUNT('Returns Data'[ReturnID])),
    [Total Orders],
    0
)
// Result: 0.0
```

### Customer Metrics
```dax
Total Customers = 
DISTINCTCOUNT('Customer Lookup'[CustomerKey])
// Result: 10.5K

Revenue per Customer = 
DIVIDE([Total Revenue], [Total Customers], 0)
// Result: $0.1

Top 100 Customers Revenue = 
CALCULATE(
    [Total Revenue],
    TOPN(100, 
        ALL('Customer Lookup'),
        [Total Revenue],
        DESC
    )
)
```

### Time Intelligence
```dax
Monthly Revenue = 
CALCULATE(
    [Total Revenue],
    DATESMTD('Calendar Lookup'[Date])
)
// Current: $1.83M

Previous Month Revenue = 
CALCULATE(
    [Total Revenue],
    DATEADD('Calendar Lookup'[Date], -1, MONTH)
)
// Previous: $1.77M

MoM Revenue Change % = 
DIVIDE(
    [Monthly Revenue] - [Previous Month Revenue],
    [Previous Month Revenue],
    0
)
// Result: +3.31%

Previous Month Orders = 
CALCULATE(
    [Total Orders],
    DATEADD('Calendar Lookup'[Date], -1, MONTH)
)

MoM Orders Change % = 
DIVIDE(
    [Monthly Orders] - [Previous Month Orders],
    [Previous Month Orders],
    0
)
// Result: -0.86%
```

### Product Performance
```dax
Adjusted Profit = 
VAR PriceAdjustment = SELECTEDVALUE('Price Adjustment (%)'[Adjustment], 0)
RETURN
    [Total Profit] * (1 + PriceAdjustment)

Orders by Category = 
CALCULATE(
    [Total Orders],
    ALLEXCEPT('Product Categories Lookup', 
              'Product Categories Lookup'[CategoryName])
)
// Accessories: 17.0K | Bikes: 13.9K | Clothing: 7.0K

Product Revenue Rank = 
RANKX(
    ALL('Product Lookup'),
    [Total Revenue],
    ,
    DESC,
    DENSE
)
```

### Target Tracking
```dax
Monthly Orders Target = 530

Orders vs Target % = 
DIVIDE([Monthly Orders], [Monthly Orders Target], 0)
// Example: 265 / 530 = 50%

Monthly Revenue Target = 1494

Revenue vs Target % = 
DIVIDE([Monthly Revenue], [Monthly Revenue Target], 0)
// Example: $1,225 / $1,494 = 82%

Monthly Profit Target = 935

Profit vs Target % = 
DIVIDE([Monthly Profit], [Monthly Profit Target], 0)
// Example: $767 / $935 = 82%
```

### Customer Segmentation
```dax
Customer Income Level = 
SWITCH(
    TRUE(),
    'Customer Lookup'[Income] >= 100000, "High",
    'Customer Lookup'[Income] >= 50000, "Average",
    "Low"
)
// High: 1.3K | Average: 9.5K | Low: 4.8K

Orders by Income = 
CALCULATE(
    [Total Orders],
    ALLEXCEPT('Customer Lookup', 'Customer Lookup'[Income Level])
)
```

---

## 🎨 Report Features

### Navigation
- 📑 9 interactive report pages
- 🔍 Drill-through on customers and products
- 🏠 Navigation buttons on left sidebar
- 📊 Consistent layout across all pages

### Interactivity
- 🎯 Cross-filtering across all visuals
- 📅 Date range slicer with "Start of Month" functionality
- 🌍 Geographic filters (Select all, Europe, North America, Pacific)
- 🎚️ Price adjustment slider (0.20 increment)
- 🔘 Product metric selection (Orders, Revenue, Profit, Returns, Return %)
- 📈 Tooltip-enabled charts for detailed information

### Visual Elements
- 🎨 Professional dark theme with blue accent colors
- 📊 Gauge charts for target vs actual performance
- 🗺️ Bing Maps integration for geographic visualization
- 📈 Area charts with confidence bands for trend analysis
- 🎯 KPI cards with month-over-month change indicators
- 📊 Data tables with conditional formatting
- 🔵 Donut charts for categorical breakdown

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create! Any contributions are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👤 Author

**Mohammed Misabahuddin**

- 📧 Email: [your.email@example.com](missuumair@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/yourprofile](https://www.linkedin.com/in/mohammed-misabahuddin-834a23222/)
- 🐙 GitHub: [@missuumair](https://github.com/missuumair)


---

## 🙏 Acknowledgments

- Microsoft for the AdventureWorks sample database
- Power BI community for inspiration and best practices
- Contributors and users of this project

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

**Made with ❤️ and Power BI**

</div>

---

## 📚 Additional Resources

- [Power BI Documentation](https://docs.microsoft.com/power-bi/)
- [DAX Guide](https://dax.guide/)
- [AdventureWorks Database Documentation](https://docs.microsoft.com/sql/samples/adventureworks-install-configure)
- [Power BI Community](https://community.powerbi.com/)

---

## 📈 Project Stats

![GitHub stars](https://img.shields.io/github/stars/missuumair/Power-BI-Report-Adventure-Works-?style=social)
![GitHub forks](https://img.shields.io/github/forks/missuumair/Power-BI-Report-Adventure-Works-?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/missuumair/Power-BI-Report-Adventure-Works-?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/missuumair/Power-BI-Report-Adventure-Works-)

---

## 📊 Quick Stats Summary

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | $24.9M |
| 📈 Total Profit | $10.5M |
| 📦 Total Orders | 25.2K |
| 👥 Unique Customers | 10.5K |
| 🔄 Return Rate | 0.0% |
| 🌍 Territories | 6 regions |
| 📅 Time Period | 2020-2022 |
| 📑 Report Pages | 9 interactive pages |
