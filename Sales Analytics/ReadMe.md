# Project Overview
This Power BI project showcases an in-depth sales analytics dashboard for TechSavvy, a technology gadgets and appliances company. The dashboard provides comprehensive insights into sales performance, profitability, and operational metrics.

![image](https://github.com/ShreevaniRao/Power-BI/blob/main/Sales%20Analytics/SalesAnalyticsDashboard.png)

## Key Features

- **Interactive Sales Dashboard**: Visualize key sales metrics and KPIs for at-a-glance performance assessment.
- **Dynamic Trend Analysis**: Utilize field parameters for flexible trend comparisons across different time periods and metrics.
- **Advanced DAX Measures**: Implement complex calculations including time intelligence for deeper insights.
- **Star Schema Data Model**: Optimize data relationships for efficient querying and faster report performance.
- **Custom Visualizations**: Employ gauge charts for target vs. actual comparisons, histograms for distribution analysis, and conditional formatting for quick insights.
- **Bookmarks and Tooltips**: Enhance user experience with interactive elements for easy navigation and detailed data exploration.

## Technical Highlights

### Data Modeling:
- Implemented a **star schema** with fact and dimension tables for optimal performance.
- Established proper relationships between tables for accurate **cross-filtering**.

### DAX Measures:
- Created a dedicated measure table for centralized calculations and easy maintenance.
- Developed measures for sales, profit, and operational KPIs for comprehensive analysis.
- Implemented time intelligence calculations for **month-over-month analysis** to track **performance trends**.

### Advanced Visualizations:
- Utilized the new card visual with reference labels for clear **KPI tracking**.
- Designed dynamic trend charts using field parameters for flexible **metric comparisons**.
- Created histograms using Power BI's grouping feature for **distribution analysis**.
- Implemented gauge charts with target setting for easy **performance evaluation**.

### Interactive Features:
- Implemented bookmarks for saved views and navigation, enhancing user experience.
- Designed custom tooltips for detailed country breakdowns, providing deeper insights on hover.
- Utilized zoom sliders for granular data exploration in **time series** visualizations.

### Performance Optimization:
- Addressed and resolved **DAX calculation** issues for improved report responsiveness.
- Optimized data refresh and query performance for faster loading times.

### User Experience:
- Designed an intuitive slicer panel for easy filtering and data exploration.
- Applied conditional formatting to tables for better data interpretation at a glance.
- Implemented visually appealing slicers on the left panel for consistent navigation.

## Dashboard Components

- Sales Overview
- Product Performance Analysis
- Salesperson Effectiveness
- Geographic Sales Distribution
- Low Box Shipment (LBS) Analysis
- Profit Margin Insights
- Time-based Trend Analysis

## Deployment

The dashboard is published to Power BI Service, allowing for easy sharing and collaboration within the organization.

# Executive Summary and Recommendations

## Insights Found

### Sales Performance
- Sales showed a decline through 2024, but the company managed to maintain profitability due to effective cost management.
- The highest sales were in January 2023, while the lowest sales were in December 2024.

### Product Performance
- **Top-Selling Products**: Smartwatch GT, Fitness Tracker, and Laptop Pro 15.
- **High Average Sale Amounts**: Fitness Tracker, Smartwatch GT, and Gaming Console X.
- **Low-Performing Products**: Smartphone XR and Laptop Pro 15.

### Cost and Profit Analysis
- The company achieved a healthy profit margin of 35.03%.
- Costs were kept relatively stable, contributing to sustained profitability.

### Salesperson Performance
- **Top-Performing Salespersons**: David Brown, Carol Williams, and Alice Johnson.
- **Lower Performing Salespersons**: Bob Smith and Eva Davis.

## Operational Metrics
- Total boxes sold and shipments were significant, with efficient management contributing to overall performance.
- **High-Performing Regions**: USA and Canada.
- **Emerging Markets**: India and Australia.

### Recommendations for Improvements

1. **Focus on Top-Selling Products**
   - Concentrate marketing efforts on top-selling products like Smartwatch GT, Fitness Tracker, and Laptop Pro 15 to maximize sales.

2. **Promote High Average Sale Products**
   - Promote products with high average sale amounts, such as Fitness Tracker and Smartwatch GT, through targeted advertising campaigns.

3. **Investigate Low-Performing Products**
   - Analyze and address the reasons for the low performance of products like Smartphone XR and Laptop Pro 15.

4. **Expand Successful Products to New Geographies**
   - Expand the availability of successful products to new regions with similar demographics to boost sales.

5. **Optimize Inventory Management**
   - Ensure high-demand products are always in stock to prevent lost sales and adjust inventory levels based on sales forecasts.

6. **Enhance Product Features and Variants**
   - Introduce new features or variants for high-selling products to attract more customers.

7. **Leverage Seasonal Trends**
   - Plan marketing campaigns around seasonal trends to capitalize on high-demand periods.

8. **Recognize and Reward Top-Performing Salespersons**
   - Recognize and reward top-performing salespersons to motivate them and others to maintain or improve their performance.

9. **Provide Additional Training or Support to Low-Performing Salespersons**
   - Offer additional training or support to salespersons with lower performance to help them improve.

10. **Cost Optimization**
    - Conduct a detailed cost analysis to identify areas for cost reduction without compromising quality or customer satisfaction.

11. **Customer Feedback and Reviews**
    - Encourage customers to leave reviews and feedback to make improvements and build trust and credibility.

By implementing these recommendations, the company can optimize product sales, improve customer satisfaction, and drive overall business growth. 

## Skills Learned & Demonstrated

### Functions Learned
- **LastDate, FirstDate** for time intelligence
- **Calculate** for context modification
- **Related** for accessing related table data
- **Divide** for safe division operations
- **Edate** for date calculations
- **If** for conditional logic
- **Var + Return** for efficient measure writing

### Features Learned
- Creating **bins** for data grouping
- Creating **parameters** for dynamic visuals based on slicer selection
- Implementing **Bookmark + Selection** switch functionality for multiple views
- Using **new cards with reference values** for enhanced KPI visualization
- Setting up **gauge charts** with targets for performance tracking
- Implementing **zoom sliders** for detailed data exploration
- Inserting **images** in tables for visual enhancement
- Creating **icons** in tables based on performance indicators
- Designing **custom tooltips** for additional context
- Utilizing icons for intuitive data representation

This project demonstrates proficiency in Power BI development, from data modeling to advanced visualization techniques, showcasing the ability to create insightful and interactive business intelligence solutions tailored to derive sales business insights.

## Acknowledgments

Special thanks to **[Chandoo](https://www.youtube.com/watch?v=ooJO7NW4uJU&t=755s&ab_channel=Chandoo)** for the insightful tutorials on Power BI, which greatly assisted in the development of this dashboard.
