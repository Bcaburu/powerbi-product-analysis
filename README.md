# powerbi-product-analysis
Sales analysis project developed in Power BI to support strategic decisions for an upcoming product launch, using historical sales data to identify trends, risks, and growth opportunities.
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
