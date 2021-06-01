# Citi Bike Dashboard

Tools: Python, Power BI

Data Source: https://s3.amazonaws.com/tripdata/index.html

This dashboard was built using monthly data from Citi Bike. The data was imported and concatenated using Python and the final export was exported in construction of the dashboard. The dashboard was created using Power BI and will further analyze the various stations of Citi Bike and the bike inventory to assist with supply chain analysis. Data examined in the dashboard is dated from November 2019 to February 2020.

## Dashboard Report #1
![Station Dashboard](asset/images/Dashboard_1.PNG)

The first dashboard examined the station and their popularity from count of trips. In the map, it demonstrates count of trips at both the start station and the end station. The ends stations circled identified that the customers do not start their trip at those locations but end their trip at those circled stations. This could be a inventory issue as if no one starts at this station but return the bikes at these stations to end their trip, those stations will continue to accumulate more and more bikes causing an uneven distribution of inventory. It would be advisable to redistribute those bikes every month or how ever long of a period the company desires to stations that need them more. In the bottom right quadrant contains a heat meat for the number of trips that occurs for each day of the week and the hour the trip started and stopped. This heat meat can help indicate hour of operations when numbers of trips are low and could be brought in for repairs and maintenace or display peak hours and when to ensure start stations and end stations are well supplied.

## Dashboard Report #2
![Bike Location Dashboard](asset/images/Dashboard_2.PNG)

The second dashboard gives you a live feed on bike locations. On the map, it displays the total bikes at each station presently or in this case the latest trip time of each bike (bike id). These map and tables can be adjusted to showcase live locations with the inclusion of the most recent trips dataset. The company can use the map with the addition of the table of bike totals in each station to review if any bikes needs to be redistributed, for example if an unpopular station has many bikes we may want to redistribute those bikes to a more popular station or vice versa. In addition, the table in the left bottom corner exhibits the bikes in the company's inventory and the number of trips the bike has been ridden. The company could set a benchmark that when a bike has reached a certain amount of trips that they should bring the bike in for maintenace or repairs. 

