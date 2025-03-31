# Super Store Return Rates
What is causing the high number of returned orders at the Superstore? In this project, I prepared an analysis to understand what is causing customers to return their orders and how to reduce the volume of returned orders.

Tableau Link: https://public.tableau.com/views/SalesReturnSuperStore/StoryUnderstandingReturnRates?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Video Overview: https://drive.google.com/file/d/1n9Nw600o00GFxdDsgetBtUaAtx9-Hdzx/view?usp=sharing


# Data
* 'Superstore.xls': each row corresponds to one product sold; sheets were LEFT JOIN'd
  * 'orders': details all fields for each ordered item
  * 'returns': details all fields for each returned item
 
# Description
This project is a Tableau workbook consisting of visualizations, stories, and dashboards with the purpose of understanding what is causing customers to return their orders and how to reduce the volume of returned orders.

# Assumptions
* Operations and marketing departments will need to make changes to increase profitability.

# Process
I joined sheets within Tablea. Then I analyzed the data using visualizations to determine what is causing returns. I built multiple dashboard for monitoring and analyzing returns. Lastly I created multiple Tableau stories to present my findings.

# Findings
Exploring the data from a high level is important for proper analysis and continued monitoring over time to create a dashboard to provide key stake holders the ability to monitor returns from a high level for region, month/quarter, category, and subcategory. 

During this exploratory analysis, it’s clear that region and month/category are the key root causes of returns as these dimensions best paint the picture of where returns are coming from.

Returns need to be minimized to ensure proper flow of goods and a healthy product life cycle. It is clear that purchases made during Q3 and Q4 in the West region have the highest return rates. It is also clear that purchases made in Q1 and Q2 in the Central region had the lowest return rates. In order to minimize returns and maximize profits I recommend doing the following:

* Increasing marketing efforts in Q1/Q2 in all regions, but making the largest investment in the Central region
* Decreasing marketing efforts in Q3/Q4 in West region
* Reward those customers that have a low return rate by providing discounts codes to motivate them to buy more
* Create look-a-like audiences based off customers who have lowest return rate to target in marketing efforts
* Increase training for Super Store employees to become more knowledgable on products to help educate customers to ensure customers are buying the right product for their needs
* Consumer behavior changes over time and so will return rates as the above changes are implemented.

Return rates should be monitored on a consistent basis with both dashboards to determine if key root causes for returns also change.
