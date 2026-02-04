# Sales Data Analysis - Power BI Project

## 📊 Project Overview

This Power BI project provides comprehensive sales analytics for **ElectroHub**, enabling data-driven decision-making through interactive visualizations and key performance indicators. The dashboard transforms raw sales data into actionable insights, covering sales performance, profitability analysis, product analysis, and promotional effectiveness.

## 🎯 Business Objectives

The dashboard addresses the following key business questions:

1. **Product Performance**: Identify top and bottom 5 products by sales, profit, and quantity sold
2. **Sales Trends**: Analyze how sales trends vary over time (daily, monthly, quarterly, annually)
3. **Profitability Analysis**: Understand the relationship between sales and profit
4. **Period Comparison**: Compare sales/profit/quantity sold between any two user-selected periods
5. **Promotion Effectiveness**: Evaluate average discount offered in each discount category
6. **Order Tracking**: Monitor total number of orders
7. **Detailed Transactions**: View sales, profit, discount, net sales, and all remaining fields with dynamic filtering
8. **Geographic Analysis**: Show sales performance by different cities

## 📸 Dashboard Preview

### Main Dashboard
- **Total Orders**: 3,510 orders processed
- **Sales Trends**: Historical sales data from 2020-2024
- **Profit vs Net Sales**: Correlation analysis showing strong positive relationship
- **Promotional Impact**: Average discount analysis by promotion type

### Key Features Visualization
- Top 5 and Bottom 5 products by Sales, Profit, and Quantity
- Period comparison with dual date filters
- Interactive filters (Product, Date, Customer ID, Promotion)
- Detailed transaction table with full order information

## 🔧 Technical Implementation

### Data Source
- **Source**: Excel file
- **Company**: ElectroHub
- **Data Type**: Sales transactions with customer, product, and promotion details

### Data Processing
- **Data Cleaning**: Performed in Power Query
  - Removed duplicates and null values
  - Standardized data formats
  - Validated data integrity
  
- **Data Profiling**: 
  - Column quality assessment
  - Data distribution analysis
  - Identified and handled outliers

- **Data Modeling**:
  - Established relationships between tables
  - Created star schema for optimal performance
  - Implemented proper cardinality and cross-filter direction

### DAX Measures
Custom measures created include:
- Total Sales
- Total Profit
- Net Sales
- Average Discount
- Total Orders
- Profit Margin %
- Period-over-Period comparisons
- Top/Bottom product rankings

## 📊 Key Metrics & KPIs

| Metric | Description |
|--------|-------------|
| **Total Orders** | 3,510 orders |
| **Net Sales** | ~122M total revenue |
| **Total Profit** | ~12.2M profit generated |
| **Total Quantity** | 7,125 units sold |
| **Date Range** | 2020-2024 |

## 🎨 Dashboard Features

### Interactive Filters
- **Date Filter 1 & 2**: Compare any two time periods
- **Product Name**: Filter by specific products
- **Customer ID**: Analyze customer-specific transactions
- **Promotion Name**: View promotion-specific performance

### Visualizations
1. **Card Visuals**: Total order count
2. **Bar Charts**: Top/Bottom 5 products analysis, Average discount by promotion
3. **Scatter Plot**: Profit vs Net Sales correlation
4. **Line Chart**: Sales trends over time
5. **Column Charts**: Period comparison visuals
6. **Table**: Detailed transaction-level data

### Analytical Capabilities
- **Drill-through**: Navigate from summary to detailed views
- **Cross-filtering**: Interactive filtering across all visuals
- **Dynamic Period Comparison**: Select and compare any two date ranges
- **Promotion Analysis**: Evaluate effectiveness of different promotional strategies

## 💡 Key Insights

Based on the dashboard analysis:

- **Top Performing Products**: Apple iPhone 14 leads in sales (22.5M), profit (2.14M), and quantity (281 units)
- **Promotional Strategy**: Weekend Flash Sale offers the highest average discount (22.6K)
- **Sales Pattern**: Clear upward trend from 2020 to 2024 with seasonal variations
- **Profitability**: Strong positive correlation between net sales and profit
- **Product Range**: Clear distinction between high-value electronics and low-value household items

## 🛠️ Technologies Used

- **Power BI Desktop**: Dashboard creation and visualization
- **Power Query**: Data transformation and cleaning
- **DAX (Data Analysis Expressions)**: Custom measures and calculations
- **Excel**: Source data storage

## 📈 Future Enhancements

Potential improvements for the dashboard:
- [ ] Customer segmentation analysis
- [ ] Predictive analytics for sales forecasting
- [ ] Inventory management integration
- [ ] Regional performance heat maps
- [ ] Customer lifetime value (CLV) calculation
- [ ] Mobile-optimized report layout
- [ ] Real-time data integration via API

## 👤 Author

**Dhaval Patel**
- GitHub: https://github.com/Dhaval1512
- LinkedIn: https://linkedin.com/in/dhavalp1512
- Email: pdhaval0405@gmail.com

## 🙏 Acknowledgments

- ElectroHub for providing the sales data
- Power BI community for inspiration and best practices
- Microsoft for Power BI platform and documentation

## 📞 Contact & Support

For questions, suggestions, or issues:
- Open an issue in this repository
- Contact via email: pdhaval0405@gmail.com
- Connect on LinkedIn

---
