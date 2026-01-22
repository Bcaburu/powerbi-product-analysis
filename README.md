# powerbi-product-analysis
Sales analysis project developed in Power BI to support strategic decisions for an upcoming product launch, using historical sales data to identify trends, risks, and growth opportunities.
# 🛠️ Tools & Technologies
- Power BI
- DAX
- Power Query
- Data Modeling
- Data Visualization
# 🎯 Business Context
The company is preparing to launch a new product line next quarter and requested an in-depth analysis of recent sales data to better understand customer preferences, product performance, and potential risks before the launch.
# 👥 Stakeholders
- Sales Team: identify high-performing products and categories
- Marketing Team: guide campaign and positioning strategies
- Product Team: support decisions on product design and portfolio focus
# 📊 Data Sources & Limitations
The analysis is based on a single sales dataset containing product, order, customer, and payment information.
The available data covers a short time period (February 1, 2023 to March 28, 2023), which limits deeper temporal analysis such as YoY, MoM, and weekday trends.
# 🧹 Data Import & Cleaning (Power Query)
Data preparation was performed using Power Query, including:
- Text formatting and cleanup
- Handling missing values for product descriptions and subcategories
# 🧮 Data Modeling & DAX
To support the analysis, additional modeling and DAX logic were implemented:
- Calendar table created using DAX to enable time-based analysis
- Measures adjusted to return zero instead of blank values for more accurate visuals
- Products classified into price tiers (Entry-Level, Core, Premium) based on price distribution
- Percentage-based measures were created to compare product share versus revenue contribution, displayed via tooltips to enhance insight without cluttering visuals
# 📊 Dashboard Overview
![Dashboard Overview](https://github.com/Bcaburu/powerbi-product-analysis/blob/main/images~/DashboardOverview.JPG?raw=true)
# 🔍 Insights & Recommendations
**📅 Data Coverage**  

**Insight:** The limited time range restricts advanced trend analysis.  
**Recommendation:** Incorporate additional historical data for future analyses.

**🚴 Product Category Performance**

![Revenue byCategory](https://github.com/Bcaburu/powerbi-product-analysis/blob/main/images~/RevenuebyCategory.JPG?raw=true)  
**Insight:** Mountain and Touring bikes generate the highest revenue among processed and shipped orders.  
**Recommendation:** Prioritize these categories for the new product launch.

**❌ Order Cancellations**

![Cancelation byCategory](https://github.com/Bcaburu/powerbi-product-analysis/blob/main/images~/CancelationbyCategory.JPG?raw=true)  
**Insight:** Road bikes account for the majority of canceled orders, indicating a category-specific issue.  
**Recommendation:** Reassess pricing, positioning, or operational factors related to Road Bikes.

**💰 Premium Products**

![Premium Products](https://github.com/Bcaburu/powerbi-product-analysis/blob/main/images~/PremiumProducts.JPG?raw=true)  
**Insight:** Among processing and shipped orders, premium products account for only 21% of the product portfolio but generate 32% of total revenue.  
![Top Four Products](https://github.com/Bcaburu/powerbi-product-analysis/blob/main/images~/TopFourProducts.JPG?raw=true)   
**Evidence:** The four most ordered products are all classified as premium, reinforcing the strong revenue impact of higher-priced items despite their lower representation in the catalog.  
**Recommendation:** Use premium product characteristics as benchmarks for the new product line, especially for positioning and pricing strategy.
