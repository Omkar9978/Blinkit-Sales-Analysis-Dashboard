# Blinkit Sales Analysis - Power BI Dashboard
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

## Dashboard

### Dashboard Overview
- Interactive Power BI dashboard providing insights into sales, outlets, and customer behavior.
### Dashboard Image
<p align="center">
  <img src="https://github.com/Omkar9978/Blinkit-Sales-Analysis-Dashboard/blob/main/Blinkit%20Dashboard-img.png">
</p>



### Dashboard Components

#### Filter Panel (Left Side)
- **Outlet Location Type**: Tier 1, Tier 2, Tier 3
- **Outlet Size**: Small, Medium, High
- **Item Type**: 16 product categories

#### KPI Cards (Top)
- **Total Sales**: $1.20M
- **Average Sales**: $141
- **Number of Items**: 8,523
- **Average Rating**: 3.9

#### Visualizations
- **Fat Content by Outlet**: Donut chart comparing Low Fat ($776.32K) vs Regular ($425.36K).
- **Item Type Sales**: Horizontal bar chart ranking all 16 item categories by sales.
- **Fat Content Analysis**: Donut chart showing 64.6% Low Fat vs 35.4% Regular contribution.
- **Outlet Establishment Trend**: Line chart (2012–2022) with peak sales in 2018 ($205K).
- **Outlet Size Distribution**: Donut chart showing High (42.3%), Small (37.0%), Medium (20.7%).
- **Outlet Location Performance**: Bar chart comparing Tier 3 (39.3%), Tier 2 (32.7%), Tier 1 (28.0%).
- **Outlet Type Matrix**: Detailed table with Total Sales, Number of Items, Average Sales, Ratings, and Item Visibility.

---

## Project Insights
- Low-fat products dominate sales with **64.6% contribution ($776.32K)**, indicating strong health-conscious customer preference.
- Tier 3 cities outperform Tier 1 with **39.3% of total sales**, revealing untapped growth potential in smaller cities.
- **Supermarket Type 1** accounts for **65.6% of total sales ($787.55K)**, making it the most scalable outlet model.
- **Fruits & Vegetables (14.8%)** and **Snack Foods (14.7%)** are the top-performing categories.
- Categories like **Seafood (1.0%)** and **Breakfast (1.5%)** significantly underperform.
- High-capacity outlets contribute **42.3% of total sales**, demonstrating higher efficiency than medium-sized outlets (20.7%).
- Item visibility remains consistently low (0.06–0.10) across outlets, presenting a **20–30% sales improvement opportunity**.
- Average customer rating of **3.9** reflects good satisfaction but highlights scope for improvement.

---

## Final Conclusion

To maximize Blinkit's sales and market expansion, the company should prioritize aggressive growth in Tier 3 cities, which contribute the highest share of total sales (39.3%) and offer lower competition with significant untapped potential. The business should replicate and scale the Supermarket Type 1 outlet format, as it generates 65.6% of total sales, while expanding low-fat and health-focused product offerings to align with strong customer preference (64.6%). Improving item visibility from the current range of 0.06–0.10 to the industry standard of 0.15+ through better merchandising can unlock an estimated 20–30% increase in sales. Additionally, underperforming categories such as Seafood and Breakfast should be revitalized through targeted promotions, while service quality improvements aimed at raising average customer ratings from 3.9 to 4.2+ will strengthen customer retention and competitive positioning. Converting medium-sized outlets into high-capacity formats and introducing private-label products in health segments will further diversify revenue streams, positioning Blinkit for an estimated 15–20% growth in the quick-commerce grocery market.
 in the quick-commerce grocery segment.



