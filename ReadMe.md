# City Bike Analysis

## Project Overview
This project analyzes city bike usage data from 2023 and 2024 for the month of August. Focusing on ridership trends, station popularity, and common routes. The analysis aims to provide insights for city officials to enhance bike-sharing programs and improve urban mobility.

[TABLE PUBLIC WORKBOOK](https://public.tableau.com/views/Bike_Ride_NJ_NYC/Story1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


### Data Sources
The analysis uses two CSV files containing bike usage data for the years 2023 and 2024. The primary fields of interest include:

ride_id: Unique identifier for each ride.
started_at: Timestamp for when the ride started.
ended_at: Timestamp for when the ride ended.
start_station_name: Name of the station where the ride started.
end_station_name: Name of the station where the ride ended.
member_casual: Indicates whether the rider is a member or a casual user.

### ETL Pipeline 
The analysis includes several key components:

#### Data Cleaning:

Data entry errors have been removed, and columns are correctly typed. Null values have been handled appropriately to ensure the accuracy of the analysis. Data types have been changed for conversion purposes. 
Time of ride was removed to focus only only on date for the purpose of reducing the data in order to manipulate it more easily in Tableau. 

#### Visualizations:

A static map showing bike stations with visual indications of popularity, station name and being able to switch between years.
Line graphs showing ridership growth for the years 2023 and 2024.
A bar chart comparing the top ten and bottom ten bike stations.
A visualization of the most common routes taken by users.
Circle graphs showing member vs. casual riders and prefered days of travel. 

#### Trends and Insights:

Analysis describing ridership behavior and highlighting trends in bike usage.
Insights into the most popular routes and how station popularity varies within the month of August.

* Total Ridership Growth: The total ridership has slightly decreased for the month of August from 2023 to 2024, indicating decrease usage of the bike-sharing program.
* Popular Stations: The top stations were identified by start and end of the journeys. These stations tend to be the same with Grove St Path being the most popular station to start and end journeys. Followed by Hoboken Terminal. 
* Common Routes: The analysis provided a list of the most common routes taken by bikers, this is useful for city officials in case of building planning and constructions. The most popular route being Hoboken Terminal to Hudson St. 
* Monthly Trends: variations in ridership were examined, showing peak usage during certain says of the week, Thursday being the most popular, followed by Tuesday.
* Consumer Insight: Most riders tend to have a membership in the City bike program as oppposed to Casual Riders. The most popular journey is taken on Tuesdays by members, which tells us that communiting to work is involved. On the other hand, Casual members prefer Sunday, a leisure day for most who do not have work. 


## Conclusion
This analysis provides valuable insights into city bike usage, helping city officials make informed decisions regarding bike-sharing programs. By understanding ridership patterns and trends, cities can enhance bike infrastructure and promote sustainable urban transport.

