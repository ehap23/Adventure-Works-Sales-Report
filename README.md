# AdventureWorks Sales Power BI Report Project

## Project Objective
Design and develop an interactive Power BI dashboard to provide the management team of **AdventureWorks**, a global manufacturer of cycling equipment and accessories, with a comprehensive view of their business performance.

---

## Skills Demonstrated

### Data Acquisition & Transformation:
- **Successfully connected** to multiple raw CSV files containing data on transactions, returns, products, customers, and sales territories.
- Utilized **Power Query Editor** to clean, transform, and prepare the data for analysis.
- Applied **data profiling techniques** to explore data quality, composition, and distribution.
- Performed various data transformations including:
  - Extracting, cleaning, and shaping data.
  - Adding new columns, modifying existing values, grouping records, and sorting/filtering data.
  - Merging and appending queries to join and combine data from different tables.
  - Utilizing text, numerical, and date/time functions for data manipulation.
  - Creating conditional columns based on logical rules and conditions.

### Data Modeling:
- Designed and implemented a robust relational data model using a **star schema** with connected dimension tables.
- Extended the model's depth with additional product tables in a **snowflake schema**.
- Managed relationship cardinality (**one-to-many**, **one-to-one**) and filter flow within the model.
- Controlled filter propagation and analysis using active and inactive relationships.
- Addressed potential issues like **filter context ambiguity** and **bi-directional filters**.
- Created **hierarchies** to facilitate drill-down analysis at various granularities.

### DAX (Data Analysis Expressions):
- **Calculated Columns**:
  - **Customer Priority**: Categorized customers as "Priority" or "Standard" based on parental status and income level.
  - **Income Level**: Segmented customers into "Very High," "High," "Average," and "Low" income brackets.
  - **SKU Category**: Extracted the SKU category from the `ProductSKU` column.
- **Measures for KPIs & Insights**:
  - **Total Customers**: Distinct count of customers who made transactions.
  - **Return Rate**: Percentage of returned items vs. items sold.
  - **Bike Returns**: Total quantity of returned bikes.
  - **Bike Sales**: Total quantity of bikes sold.
  - **Bike Return Rate**: Rate of bike returns as a percentage of sales.
  - **All Returns**: Total number of returns across all filters.
  - **% of All Returns**: Percentage of returns by product category.
  - **Total Cost**: Order quantity multiplied by product cost.
  - **Total Profit**: Total revenue minus total cost.
  - **Time Intelligence Measures**: Month-over-month and year-over-year comparisons for returns, orders, and profits.

### Data Visualization and Reporting:
- Designed a Report comprising **multiple report pages**, tailored for diverse audiences.
- Employed visuals such as **cards, line charts, donut charts, tables, maps, and slicers**.
- Applied **conditional formatting** to highlight trends and insights.
- Enabled **drill-down and drill-through filters** for multi-level analysis and navigation.
- Utilized **bookmarks** for storytelling and highlighting specific insights.
- Configured interactions for intuitive user experience and flexibility.
- Incorporated **field parameters** to allow dynamic control of displayed metrics.
- Followed **data visualization best practices** for clarity and simplicity.

---

## Additional Features & Tools
- **Optimization Tools**: Enhanced report performance using the Optimize ribbon and Performance Analyzer.
- **External Tools**: Considered tools like DAX Studio, ALM Toolkit, Tabular Editor, and Python for advanced optimization.
- **Mobile Layout**: Created mobile-optimized layouts to ensure usability across devices.

---

## Project Outcome
This project demonstrates proficiency in **Power BI**, covering data acquisition and transformation, data modeling, DAX calculations, and interactive visualization techniques. The dashboard provides a robust platform for data exploration, analysis, and decision-making for AdventureWorks.

![Power BI Dashboard Screenshot]()
> [View the live Report on Power BI Server]([https://your-powerbi-server-link/dashboard](https://app.powerbi.com/reportEmbed?reportId=35607cbc-bd56-47a2-9161-7ae0b32d0955&autoAuth=true&ctid=681e3d57-b8ae-4fbd-a826-02bf07599ccb))
