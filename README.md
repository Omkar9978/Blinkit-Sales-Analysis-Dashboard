# Blinkit Grocery Sales Analysis - Power BI Dashboard
## Project Objective
Blinkit (India's Last Minute App) wants to conduct a comprehensive analysis of their sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization. The goal is to analyze various KPIs and visualizations in Power BI to help the business understand sales patterns, customer preferences, and outlet performance to drive strategic decisions for business growth and optimization.
## Dataset Used
- <a href="https://github.com/Omkar9978/Blinkit-Sales-Analysis-Dashboard/blob/main/BlinkIT%20Grocery%20Data.xlsx">Blinkit Sales Data</a>
## Questions (KPIs)

### Primary Metrics
- **Total Sales**: What is the overall revenue generated from all items sold?
- **Average Sales**: What is the average revenue per transaction?
- **Number of Items**: How many different items are being sold?
- **Average Rating**: What is the average customer rating?

### Analytical Questions
- How does fat content (Low Fat vs Regular) impact total sales?
- Which item type generates the highest sales revenue?
- How is fat content distributed across different outlets?
- What is the relationship between outlet establishment year and sales performance?
- How do different outlet sizes contribute to total sales?
- Which outlet location type generates maximum sales?
- What is the sales distribution across different outlet types?
- How does item visibility vary across outlet types?
- What is the relationship between outlet type and average sales?
- Which geographic tier (Tier 1, Tier 2, 3) contributes most to sales?


## Process

### Step 1: Data Verification
- Checked the dataset for missing values, anomalies, and inconsistencies.
- Identified 1,463 missing values in the Item Weight column (17.2%).
- Detected inconsistent Item Fat Content labels.

### Step 2: Data Cleaning
- Standardized Item Fat Content values (LF, low fat, reg) into consistent categories (Low Fat, Regular).
- Ensured data consistency across data types, formats, and values.

### Step 3: Data Modeling
- Loaded the cleaned dataset into Power BI.
- Established proper data model relationships.
- Verified data integrity after modeling.

### Step 4: DAX Calculations
- Created calculated measures using DAX, including:
  - Total Sales
  - Average Sales
  - Number of Items
  - Average Rating
- Implemented percentage and comparative calculations.

### Step 5: Visualization Design
- Designed interactive visuals including:
  - KPI Cards for primary metrics
  - Donut Charts for fat content and outlet size distribution
  - Bar Charts for item type and outlet location analysis
  - Line Chart for outlet establishment year trends
  - Matrix Table for detailed outlet type performance

### Step 6: Dashboard Creation
- Combined all visuals into a single interactive dashboard.
- Added filter panels for:
  - Outlet Location Type
  - Outlet Size
  - Item Type
- Enabled dynamic and drill-down analysis.

### Step 7: Insight Generation
- Analyzed trends and patterns across all KPIs.
- Derived actionable business insights to support strategic decision-making.


