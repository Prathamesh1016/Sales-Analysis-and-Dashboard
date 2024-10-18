Data Visualization Dashboard:  (Tableau)   
Tools Used:

Tableau Desktop: For data visualization and dashboard creation.

MS SQL Server: For data storage, management, and querying.

Problem Statement:

The goal of this project was to create a dynamic and interactive sales dashboard for a pizza restaurant, enabling business stakeholders to gain insights into pizza sales trends, best and worst sellers, and sales performance over different time ranges. The restaurant needed a solution to track their sales data, identify popular pizza categories, and analyze sales over time to make informed business decisions.

Project Execution:

Data Import and Storage:

Imported the sales data (CSV files) into MS SQL Server using the "Import Flat File" wizard.

Created a relational database to store the data and performed necessary transformations, such as handling duplicate records using DISTINCT queries.

Data Modeling:

Built queries to calculate key metrics, including the total number of pizzas sold, average pizzas per order, and the percentage of total sales by pizza category.

Developed SQL queries to fetch and aggregate data, handling numerical precision and calculating metrics like total revenue and average order value.

Dashboard Development:

Designed a dynamic, interactive Tableau dashboard to visualize key insights. This dashboard included:

Date range filters to analyze sales over specific periods.

Pizza category filters to show insights for specific pizzas like "Chicken Pizza" or "Veggie Pizza."

Navigation buttons to switch between multiple dashboards, such as "Home" and "Best/Worst Sellers."

Created visualizations such as bar charts, Gantt charts, and pie charts to represent sales performance.

Enhancements:

Styled the dashboard with custom backgrounds, borders, and label formats for a polished look.

Used PowerPoint to design a gradient background for the dashboard, improving visual appeal.

Formatted currency values and optimized the display of metrics like total sales and average order value in Tableau.

Insights and Results:

Best and Worst Sellers:

Identified the top-performing and worst-performing pizza categories based on total sales.

Provided actionable insights for stakeholders to adjust inventory or promotions accordingly.

Sales Trends:

Visualized sales trends over time using date range filters, helping stakeholders understand seasonal or daily demand fluctuations.

Enabled the business to filter by specific pizza categories (e.g., "Chicken Classic") to see category-specific sales data and inform decisions about product offerings.

Customer Behavior:

Calculated the average number of pizzas per order, helping the business understand purchasing patterns and informing marketing strategies like bundle offers.

Data Accuracy:

Ensured data integrity by removing duplicates and applying appropriate aggregations in SQL, leading to more reliable insights and business decisions.
