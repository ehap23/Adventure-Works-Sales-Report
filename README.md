# 🌟 AdventureWorks Sales Power BI Report Project

---

## 🎯 **Project Objective**
Design and develop an interactive **Power BI Dashboard** to provide the management team of **AdventureWorks**, a global manufacturer of cycling equipment and accessories, with a **comprehensive view of their business performance**.

---

## 🛠️ **Skills Demonstrated**

### 1️⃣ **Data Acquisition & Transformation**
- **Successfully connected** to multiple raw CSV files containing data on:
  - Transactions  
  - Returns  
  - Products  
  - Customers  
  - Sales Territories  
- Utilized **Power Query Editor** to:
  - Clean, transform, and prepare data for analysis.  
  - Apply **data profiling techniques** to assess data quality and composition.  
- **Key Transformations**:
  - Extracting, cleaning, and shaping data.  
  - Adding new columns and modifying existing values.  
  - Grouping, sorting, and filtering data.  
  - Merging and appending queries to join datasets.  
  - Utilizing text, numerical, and date/time functions.  
  - Creating **conditional columns** based on logical rules.

---

### 2️⃣ **Data Modeling**
- Designed and implemented a robust relational data model using a **star schema**, connected with dimension tables.
- Extended the model with **snowflake schema** to add depth and hierarchy.  
- Managed relationship cardinality (**one-to-many**, **one-to-one**) and filter flow for accurate data analysis.  
- Addressed potential filter context issues, including ambiguity and bidirectional filters.  
- Created **hierarchies** for drill-down functionality to explore data at various granularities.

---

### 3️⃣ **DAX (Data Analysis Expressions)**
- **Created Calculated Columns**:
  - **Customer Priority**: Categorized customers as "Priority" or "Standard" based on status and income.  
  - **Income Level**: Segmented customers into income brackets.  
  - **SKU Category**: Extracted SKU category from the `ProductSKU` column.  
- **Developed Key Measures**:
  - Total Customers: Count of distinct customers.  
  - Return Rate: Percentage of returned items vs. items sold.  
  - Bike Returns & Sales: Quantities and rates for bikes.  
  - Total Cost & Profit: Aggregations using **SUMX**.  
  - **Time Intelligence**: Month-over-month and year-over-year performance comparisons.

---

### 4️⃣ **Data Visualization and Reporting**
- Designed an interactive dashboard with:
  - **Cards, line charts, donut charts, tables, maps, and slicers**.  
  - Conditional formatting for highlighting trends.  
  - **Drill-through filters** for detailed analysis.  
  - **Bookmarks** for storytelling and navigation.  
  - Configured intuitive **report interactions** for seamless user experience.  
  - Incorporated **field parameters** for dynamic visualizations.

---

## 🔧 **Additional Features & Tools**
- **Optimization Tools**: Enhanced performance using the Optimize ribbon and Performance Analyzer.  
- **External Tools**: Utilized **DAX Studio**, **ALM Toolkit**, and **Python** for advanced modeling and optimization.  
- **Mobile Layout Optimization**: Ensured accessibility across devices.

---

## 🎉 **Project Outcome**
This project demonstrates proficiency in **Power BI**, encompassing data acquisition, transformation, modeling, DAX calculations, and visualization techniques. The resulting dashboard provides a robust data exploration, analysis, and decision-making platform for **AdventureWorks**.

---

### 🖼️ **Dashboard Screenshot**  
![Power BI Dashboard Screenshot]([Assets/Screenshot 2024-11-16 190549.png](https://github.com/ehap23/Adventure-Works-Sales-Report/blob/1e07453bf357f9a430f649620e54421c32f80814/Assets/Screenshot%202024-11-16%20190549.png))

> **🔗 [View the live Report on Power BI Server]([https://your-powerbi-server-link/dashboard](https://app.powerbi.com/reportEmbed?reportId=35607cbc-bd56-47a2-9161-7ae0b32d0955&autoAuth=true&ctid=681e3d57-b8ae-4fbd-a826-02bf07599ccb))**

---

### 📌 **Key Insights from the Report**:
- **Overview**: Key performance metrics such as sales, returns, and profit.  
- **Regional Insights**: Performance by sales territories.  
- **Product Analysis**: Best-performing product categories and trends.  
- **Customer Segmentation**: Demographics and customer priority analysis.  
- **Time Trends**: Year-over-year and month-over-month analysis.


