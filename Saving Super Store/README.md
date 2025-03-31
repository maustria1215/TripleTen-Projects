# Saving Super Store
The purpose of this project was to review superstore’s operations and increase its profitability to avoid bankruptcy.

Tableau Link: https://public.tableau.com/views/Saving_Super_Store/CustomerswithHighestReturnRate?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Data
* 'Superstore.xls': each row corresponds to one product sold; sheets were LEFT JOIN'd
* 'orders': details all fields for each ordered item
* 'returns': details all fields for each returned item

# Description
This project is an 11 page Tableau Public workbook. Each page showcases a different way to visualize data and addresses a specific inquiry. A description of each visualization can be found in the findings portion below.

# Assumptions
* Operations department needs direction for what items to focus on or stop selling
* Advertising department needs recommendations

# Process
* Multiple sheets were joined within Tableau Public
* Profit and loss centers were determined
* A visualization was created for each part of the project (detailed below)

# Findings / Visualization Write-ups
Part 1.1 The analysis was carried out using the Sub-Category and Region dimensions. The top two proﬁt centers were: Copiers + West and Copiers + East (see Top 3 Most Proﬁtable Sub-Categories for Each Region sheet for visualization support). The two biggest loss-makers were: Tables + East and Tables + South (see Top 3 Biggest Loss Making Sub-Categories for Each Region sheet for visualization support).

Part 1.2 Superstore should stop selling these ﬁve products as they create the most loss: GBC DocuBind P400 Electric Binding System, Cubify CubeX 3D Printer Double Head Print, Bush Advantage Collection Racetrack Conference Table, Lexmark MX611dhe Monochrome Laser Printer, and Cubify CubeX 3D Printer Triple Head Print. Please see the sheet titled Top 5 Products Superstore Should Stop Selling for visualization support.

Part 1.3 Superstore should focus on the following Sub-Categories as they are the three most proﬁtable: Accessories, Phones, and Copiers. Superstore should stop selling the following Sub-Categories as they are the biggest loss makers: Supplies, Bookcases, and Tables. Please see the sheet titled Proﬁt for Each Sub-Category for visualization support.

Part 2 Advertising must be targeted, timely, and must make sense ﬁnancially. In order to ensure advertising eﬀorts have a great ROI, eﬀorts must be focused in speciﬁc geographical areas and at the right time of year. This analysis was conducted to ﬁnd the best combinations for states and months of the year to advertise in.

Vermont (VT), Rhode Island (RI), and Indiana (IN) are the states with the highest average proﬁt (see sheet titled Average Pro ﬁt per Unit Sold by State for visualization support).

November had the highest average proﬁt in Vermont. December had the highest average proﬁt for Rhode Island. October had the highest average proﬁt in Indiana. Please see the sheet titled Average Proﬁt Per Month for VT, RI, IN for visualization support.

According to Corporate Finance Institute, adspend should be 1/5 of proﬁts. VT had a total proﬁt of ~$1k in November (see sheet titled Total Proﬁt for October, November, December for VT, RI, IN for visualization support) so the adspend for should be ~$200. While the overall proﬁt and adspend budget may be nominal in comparison to Superstore ’s total business, this is a great option for advertising due to VT ’s high average proﬁt as growing this consumer base could yield great results for Superstore. RI had a total pro ﬁt of ~$3k in December (see sheet titled Total Proﬁt for October, November, December for VT, RI, IN for visualization support) so the adspend for should be ~$600. While the overall proﬁt and adspend budget may be nominal in comparison to Superstore ’s total business, this is a great option for advertising due to RI’s high average proﬁt as growing this consumer base could yield great results for Superstore. IN had a total proﬁt of ~$9k in October (see sheet titled Total Proﬁt for October, November, December for VT, RI, IN for visualization support) so the adspend for should be ~$1800. While the overall proﬁt and adspend budget may be nominal in comparison to Superstore ’s total business, this is a great option for advertising due to IN’s high average proﬁt as growing this consumer base could yield great results for Superstore. While Superstore grows its business in VT, RI, and IN in these months, it can continue to reinvest more into adspend as long as the cost per acquisition stays below 1/5 of the proﬁts.

Part 3.1 Returned ﬁeld was successfully turned into a calculated ﬁeld (where null values are 0 and yes values are 1) titled Returned 1,0. Please see the data ﬁle titled Saving_Super_Store_1.csv as proof.

Part 3.2 The following products have the highest return rate (see sheet titled Products with Highest Return Rate for visualization support):

* Acco Glide Clips (100% return rate)
* Avery 500 (100% return rate)
* Bush Saratoga Collection 5-shelf Bookcase (100% return rate)
* Cannon Color ImageCLASS MF8580 Cdw Wireless Laser All-In-One printer (100% return rate)
* Cisco SPA 501G IP Phone (100% return rate)
* HP Deskjet F4180 (100% return rate)
* Okidata B401 Printer (100% return rate)
* Zebra GK420t Direct Thermal / Thermal Transfer Printer (100% return rate)
* Logitech Wireless Boombox Speaker (93% return rate)
* DAX Clear Channel Poster Frame (92% return rate)

Part 3.2.1 The following customers have the highest return rate (see sheet titled Customers with Highest Return Rate for visualization support):

* Hilary Holden (100% return rate)
* Roland Murray (100% return rate)
* Sandra Glassco (98% return rate)
* Joni Blumstein (95% return rate)
* Ted Butter ﬁeld (94% return rate)
* Andy Yotov (94% return rate)
* Seth Vernon (92% return rate)
* Patrick Ryan (91% return rate)
* Anthony Johnson (87% return rate)
* Mark Haberlin (86% return rate)

Part 3.3 Operations in Oregon, Tennessee, and Colorado have some of the highest return rates and lowest average proﬁt. See sheet titled Average Pro ﬁt vs Average Return Rate by State for visualization support.
