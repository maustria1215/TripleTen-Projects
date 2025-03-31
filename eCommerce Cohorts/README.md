# eCommerce Cohorts

In this project, I analyze raw transaction logs to turn event logs into business metrics by creating a conversion funnel, preparing the data for cohort analysis and calculating retention rates.

The Google Sheets file can be found here:
https://docs.google.com/spreadsheets/d/1KrZssx9E7wRQzM67xQTkLHjBk9iFC41-WWzdoK01Xck/edit?usp=sharing

# Data
The data was one Google spreadsheet file provided by TripleTen

*'Business Analyst Project.csv': raw transaction logs
*'raw_user_activity': Each row represents an activity, or event, by a user on the company’s website
  * 'user_id': unique customer IDs
  * 'event_type': the type of activity by the user
  * 'category_code': category of the product being viewed or purchased
  * 'brand': company that makes the product
  * 'price': price of the product, in USD
  * 'event_date': date of the user activity, in YYYY-MM-DD format
*'Table of Contents': Preformated yet empty table of contents sheet
*'Executive Summary: Preformated yet empty executive summary sheet


# Description:
This project is an 8 page spreadsheet that includes raw data, processed data, data analysis, and pivot tables. The purpose was to analyze the raw transaction logs and turn the event logs into business metrics.

# Assumptions:
* The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe
* Missing values or inconsistencies in the data are minimal and can be ignored
* The provided data format (columns, data types) is correct and consistent

# Process
* I explored, filtered, and cleaned the data
* A conversion funnel was created to better understand how users interact with the website with the intention of understanding how well the website is converting product page views into purchases
* I built acquisition cohorts based on the month of a user’s first purchase tracked cohort metrics month by month
* The finals steps of the analysis were to aggregate the purchase data into cohorts and then calculate retention rates for each cohort month by month
* Lastly I finalized formatting and documentation for the client's readability


# Findings/Executive Summary:
| Results | Synopsis |
| ----- | ----- |
| Conversion Funnel | Of the 10453 users that viewed a web page, 3036 (29.04%) continued on to open to their shopping cart and 1081 (10.34% of total users that viewed a webpage & 35.61% of those who opened their cart) purchased the item.|
| Retention Rates | Of the 32 users who made their first purchase in September 2020, 6.25% purchased again in October and 3.13% purchased again in January. None of them made another purchase in November or December. Of the 187 users who made their first purchase in October 2020, 4.81% purchased again in November, 2.14% purchased again in December, and 0.53% purchased again in January. None of them made another purchase in February 2021. Of the 238 users who made their first purchase in November 2020, 3.36% purchased again in December, 1.68% purchased again in January, and 0.42% purchased again in February. We do not have data for any user's activity for beyond February 2021. Of the 203 users who made their first purchase in December 2020, 4.43% purchased again in January, and none of them purchased again in February. We do not have data for any user's activity for beyond February 2021. Of the 233 users who made their first purchase in January 2021, 1.72% purchased again in February. We do not have data for any user's activity for beyond February 2021. We do not have any purchase data for the 188 users who made their first purchase in February 2021 to calculate retention rate for that cohort. |

| Analysis | Description |
| ----- | ----- |
| Raw Data | The raw data contains all the instances users viewed a web page, opened their shopping cart, or purchased an item between 9/24/2020 and 2/25/2021.  The data was collected from all the transactions on their website. For the analysis, the following data was used: user_id, event_type, and event_date.  Category_code, brand, and price were not used.  With the raw data only providing a limited amount of data causing it to be tough to draw great conclusions from it.  It would be more advantageous to analyze at least a full-year's worth of data to draw more solid conclusions. Also, collecting more event types would allow stronger conclusions to be drawn.  For example, being able to capture the following event types would be beneficial to the analysis: #1 adding item to cart rather than just opening their shopping cart would allow a stronger sequence of event conversion funnel as adding to cart is further along the purchasing process than simply opening the cart as users could open their empty cart at any time without moving closer to purchasing -- opening their shopping cart just simply is not as relevant as adding an item to their shopping cart #2 collecting the source of the traffic (direct, indirect, ad, etc) would make it easier to determine what types of traffic driving strategies to use. Also, the data collection seems to have bug of some sort as over 9,000 events are missing category_code, and over 1,000 events are missing brand.  Although these pieces were not used in this analysis, missing this data severely limits what analysis can be done. It would be powerful to be able to analyze what specific category code, brand name, and specific products consumers are viewing, adding to cart, and purchasing in efforts to improve UI/UX for the website, marketing efforts, etc. |
| Conversion Funnel | It's essential to understand the sequence of events to calculate conversion. A user must first view a product page before opening* their cart, and a user must open* their cart before making a purchase. A pivot table to report how many unique users created each event type was created.  Then the number of unique users that completed one step was divided by the number of users who completed the previous step. Overall, a 10.34% conversion rate of all users who viewed a product page making a purchase is an extremely strong conversion rate compared to the ecommerce industry standard of 3%.  This means that either the buyers are coming to the product page extremely motivated to buy or the content of the page is extremely compelling.  Knowing what source the traffic came from would allow us to target marketing efforts to drive more traffic from the sources with the highest conversion rates to increase sales. Opening their cart is technically not the best/most reliable metric in determining the conversion as users can easily open their cart without adding a product to it.  Adding the product to cart would be a stronger event type to capture/analyze to truly get a more accurate conversion rate for users who viewed a product page to taking a step closer to purchasing. |
| Retention Rates | In order to calculate retention rates, it's essential to first group the users into cohorts. For this analysis, users were grouped into cohorts by what month they made their first purchase in. Since we have data from 9/24/2020 to 02/25/2021, users were grouped in 6 cohorts: #1 users who made their first purchase in September, #2 users who made their first purchase in October, #3 users who made their first purchase in November, #4 users who made their first purchase in December, #5 users who made their first purchase in January, and #6 users users who made their first purchase in February.  In this analysis, the retention rate of a user illustrates what percent of users made another purchase in a different month than their original purchase was made in.  Meaning, this users who made multiple purchases in the same month but never made a purchase again would not count as a retained user.  Retention rate is essentially a measurement of the users loyalty to the website. The specific item that is being sold very much effects the 'expected' or 'desired' retention rate.  For example, a company selling cars would expect a much lower retention rate than a company selling common household goods because consumers buy cars much less often than common household goods.  Not having the specific item data, severely limits the analysis of the retention rate as it's impossible to determine if the retention rates are "good" or "bad".  For example, if a user purchased a new mouse for their home office computer it's not expected that the user would buy another mouse a month later and another mouse a month after that. Product assortment also comes into play with retention rate.  The wider the product assortment, the higher the expected retention would be. Think of how often a user would purchase from Amazon (extremely wide assortment of product type) vs Carvana (extremely narrow assortment of product type: vehicles). In this analysis, the category code of an item can help provide context to the retention rate.  The category codes help to illustrate that the retention rates are very low given how "common" the items bought are.  Efforts must be made to increase customer loyalty. A few ways to raise ecommerce retention rates include providing a great customer experience, building a rewarding loyalty program, conducting surveys to learn why or why not customers make purchases, and utilizing cross-selling strategies. NOTE: September's retention rate is not very reliable because the dataset only includes data from purchases for 7 days in September. |
