# Zuber Database
The purpose of this project was to use SQL to find patterns in the available information from competitors to understand passenger preferences and the impact of external factors on rides.

# Tasks
Task 1: Print the company_name field. Find the number of taxi rides for each taxi company for November 15-16, 2017, name the resulting field trips_amount and print it, too. Sort the results by the trips_amount field in descending order.*/
	
Task 2: Find the number of rides for every taxi companies whose name contains the words "Yellow" or "Blue" for November 1-7, 2017. Name the resulting variable trips_amount. Group the results by the company_name field.*/

Task 3: For November 1-7, 2017, the most popular taxi companies were Flash Cab and Taxi Affiliation Services. Find the number of rides for these two companies and name the resulting variable trips_amount. Join the rides for all other companies in the group "Other." Group the data by taxi company names. Name the field with taxi company names company. Sort the result in descending order by trips_amount.*/

Task 4: Retrieve the identifiers of the O'Hare and Loop neighborhoods  from the neighborhoods table.*/
	
Task 5: For each hour, retrieve the weather condition records from the weather_records table. Using the CASE operator, break all hours into two groups: Bad if the description field contains the words rain or storm, and Good for others. Name the resulting field weather_conditions. The final table must include two fields: date and hour (ts) and weather_conditions.*/
	
Task 6: Retrieve from the trips table all the rides that started in the Loop (pickup_location_id: 50) on a Saturday and ended at O'Hare (dropoff_location_id: 63). Get the weather conditions for each ride. Use the method you applied in the previous task. Also, retrieve the duration of each ride. Ignore rides for which data on weather conditions is not available.*/

# Data
* 'neighborhoods' table: data on city neighborhoods
  * 'name': name of the neighborhood
  * 'neighborhood_id': neighborhood code
* 'cabs' table: data on taxis
  * 'cab_id': vehicle code
  * 'vehicle_id': the vehicle's technical ID
  * 'company_name': the company that owns the vehicle
* 'trips' table: data on rides
  * 'trip_id': ride code
  * 'cab_id': code of the vehicle operating the ride
  * 'start_ts': date and time of the beginning of the ride (time rounded to the hour)
  * 'end_ts': date and time of the end of the ride (time rounded to the hour)
  * 'duration_seconds': ride duration in seconds
  * 'distance_miles': ride distance in miles
  * 'pickup_location_id': pickup neighborhood code
  * 'dropoff_location_id': dropoff neighborhood code
* 'weather_records' table: data on weather
  * 'record_id': weather record code
  * 'ts': record date and time (time rounded to the hour)
  * 'temperature': temperature when the record was taken
  * 'description': brief description of weather conditions, e.g. "light rain" or "scattered clouds"
 
# Description
This project is a six step SQL query that includes exploratory data analysis and investigation into the duration of rides from the Loop to O'Hare International Airport.

# Assumptions
* There isn't a direct connection between the trips table and weather_records table in the database
* neighborhood_id is the Primary Key for the neighborhoods table
* cab_id is the Primary Key for the cabs table
* trip_id is the Primary Key for the trips table
* record_id is the Primary Key for the weather_records table

# Process
1. Analyzed taxi rides by company for specific dates, sorting by trip count
2. Analyzed rides for companies containing specific keywords, grouping by company name
3. Retrieved neighborhood IDs for O'Hare and Loop
4. Categorized weather conditions by hour
5. Retrieved Saturday rides from Loop to O'Hare, including weather and duration

# Findings
* Flash Cab had the most number of rides for November 15-16
* For rides completed on November 1-7 there were two taxi companies that had blue in their name and two that had yellow in there name
* For November 1-7: Flash Cab completed 64,084 rides, Taxi Affiliation Services completed 37,583 rides, and all other taxi companies completed 335,771 rides
* The neighborhood_id for Loop is 50
* The neighborhood_id for O'Hare is 63
