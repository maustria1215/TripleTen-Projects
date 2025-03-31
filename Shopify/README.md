# Shopify
This project uses PowerBI to review the landscape of apps on the Shopify platform from publicly available Shopify websites data to determine the key factors of success with Shopify apps.

# Data
* 'shopify.xlsx': Excel Workbook containing: 
  * 'apps': Details of the apps on Shopify apps marketplace
  * 'apps_categories': Join tables to connect apps with categories
  * 'categories': Categories of the apps. Each app has multiple categories
  * 'reviews': Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

# Description
The project is a multiple page Power BI Dashboard that includes data analysis, KPI cards and charts.

# Assumptions
* The scraped data from Shopify websites is accurate
* The data in the shopify.xlsx file is complete and consistent

# Findings
* There are 7341 unique apps on Shopify
* There is a weak correlation between number of reviews and average review rating
* Developers were more likely to comment on lower rated reviews
* Pictorem had the highest number of helpful reviews
* FireApps is the most responsive app developer
