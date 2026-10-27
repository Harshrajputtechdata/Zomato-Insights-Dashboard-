Zomato Insights Dashboard | Power BI
An interactive Power BI dashboard for exploring Zomato order data, restaurant performance, customer ratings, cuisine popularity, and delivery-time patterns.
Project Overview
This project presents an overview of food-ordering activity through a Power BI dashboard. It combines KPI cards, charts, and slicers to help users explore order trends and compare restaurants, cuisines, customer locations, restaurant locations, delivery partners, and ratings.
Dashboard Features
KPI Cards
The report includes KPI cards labelled:
- Customer Satisfaction
- Total Orders
- Average Delivery Time
- Delivery Utilization (%)
- Average Order Value
Before publishing, verify that each card uses the intended aggregation in Power BI. For example, customer ratings and delivery times are often better represented by averages, while order counts should use a count of order IDs.

Visualizations
- Top 10 Restaurants — compares restaurants by order amount.
- Total Orders Over Time — explores order counts by date.
- Rating Distribution — shows the distribution of customer ratings.
- Orders by Cuisine — compares order counts across cuisines.
- Delivery Time by Customer Location — compares delivery-time values by customer location.
Interactive Filters
Use the report slicers to filter the dashboard by:
- Restaurant name
- Customer location
- Delivery partner
- Rating
- Restaurant location
- Order date (year, month, and day)
Tools & Skills
- Microsoft Power BI Desktop
- Data visualization and dashboard design
- KPI reporting
- Interactive slicers and cross-filtering
- Time-based analysis
- Restaurant and delivery performance analysis
Repository Structure
zomato-insights-dashboard/
├── README.md
├── Zomato Insights Dashboard.pbix
└── images/
    └── dashboard-overview.png

