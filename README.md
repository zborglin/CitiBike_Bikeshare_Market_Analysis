# **CitiBike - New York Analytics Storyboard and Analysis**
Tableau Application
- Interactive Analytics
- Pandas Data Transformation

## Tableau Public Application
[link to dashboard](https://public.tableau.com/profile/zachary.borglin#!/vizhome/NYC_CitiBike_Challenge_16107646727890/CitiBikeNYAnalysis?publish=yes)

## **Purpose** 
**Market Analysis to support planning a bike-share business venture** in the Des Moines, Iowa. To estimate resource needs and develop strategic, data-driven objectives, a series of Tableau data visualizations were developed. Specifically, the client's request is for an analysis of the New York CitiBike ridesharing data from the month of August in 2019. This will reflect metadata for the busiest month which will help to amplify any data signals between user types and location. 
#
This report comprises:
- **Checkout Times for Users:** *A line plot that shows the distribution of bike trip duration.*
- **Checkout Times by Gender:** *A line plot showing bike trip duration, with separate distributions by gender*
- **Trips by Weekday per Hour** *A heatmap that illustrates how ride end timing changes each weekday*
- **Trips by Gender by Weekday per Hour** *A heatmap that illustrates how ride end timing changes each weekday*
- **User Trips by Gender by Weekday** *A heatmap that illustrates how ride end timing changes each weekday*
- **Bike Utilization Circle** *A heatmap that illustrates how ride end timing changes each weekday*
- **Top Ending Locations Map** *A heatmap that illustrates how ride end timing changes each weekday*
- **Gender Breakdown** *A heatmap that illustrates how ride end timing changes each weekday*
#
These data are critical to a bike share startup's business strategy. 

## Resources
### Raw Data Source
- site: https://www.citibikenyc.com/system-data
- filename: 201908-citibike-tripdata.csv 
### Generated
- 201908-citibike-tripdata-dt.csv
- NYC_CitiBike_Challenge.ipynb
### Software: 
- Tableau Public 
- Pandas
- Jupyter Notebook

## Analysis
![Checkout Times for Users](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Checkout_Times_for_Users_lineplot.png)
### Figure 1: Checkout Times for Users
This interactive plot allows users to select data and view summarized statics. Bike checkout times are often 3-7 hours long, following a normal distribution with a left skew. This distibution helps to understand the demand for bikes and how often they may be under use. The long tail to the right of the distribution, indicates that a number of users will maintain the reservation long past the length of a typical ride. This leads to a hypothesis that riders can either maintain a bike for multiple rides, overnight, or forget to end their ride. 

![Checkout Times by Gender](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Checkout_Times_by_Gender_lineplot.png)
### Figure 2: Checkout Times by Gender
Another look at the data discussed in figure 1 with distinction by gender provides additional insight into how long different types of users sustain a bike rental. It appears that males are more likely to use a bike rental than a female.

![Gender Breakdown](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Gender_Breakdown.png)
### Figure 8: Gender Breakdown
To confirm the statement in the previous figure that males are more likely to rent a bike, this pie chart gives the gender breakdown for each ride.

![Trips by Weekday per Hour](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Trips_by_Weekday_per_Hour_Heatmap1.png)
### Figure 3: Trips by Weekday per Hour
Using color to represent the magnitude of rides that occur throughout each day of the week, a concentration of rides occur during the weekday commute hours. More consistent bike use occurs throughout the weekend days.

![Trips by Gender by Weekday per Hour](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Trips_by_Gender_Weekday_per_Hour_Heatmap2.png)
### Figure 4: User Trips by Gender by Weekday
Building on the analysis in the previous figure, the data is categorized by gender to reveal similar trends with different magnitudes. Both male and female riders exhibit similar use behavior throughout the week.

![User Trips by Gender by Weekday](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/User_Trips_by_Gender_by_Weekday_Heatmap3.png)
### Figure 5: User Trips by Gender by Weekday
To dig more deeply into how bikes are utilized throughout the week, the data is also explored in the context of user type (single use or subscriber). This reveals that most users are subscribers, and that subscribers use the bikes often throughout the week - dominating the dataset.

![Bike Utilization Circle](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Bike_Utilization_Circle.png)
### Figure 6: Bike Utilization Circle
This circle visualization is a useful way to identify bikes in potential need of repair, with larger/darker circles having the most accumulated useage.

![Top Ending Locations Map](https://github.com/zborglin/CitiBike_Bikeshare_Market_Analysis/blob/main/resources/images/Top_Ending_Locations_Map.png)
### Figure 7: Top Ending Locations Map
This map visualization gives the ending locations for teh rides recorded in August 2019. This provides insight not only into where bikes needed repair will be stored, but also where users tend to ride bikes to to enable bike distribution planning

## Summary
Four recommendations can be made from the analysis presented in this report:
1. CitiBike can expand its user base significantly if it finds better ways to connect with female users.
2. Bike repairs are best made between 2-5AM, when ridership is at a minimum.
3. Bike quantities should be determined by studying use during weekday commute hours, when there is the greatest demand.
4. Subscribers are the dominating user base for CitiBike. It brings to light that one-time users are not a large part of the business. The new venture should think of ways to better incentivize one-time use of bikes to drum up revenues.

## Next Steps
Should the client be interested in contracting for additional analysis, here are two recommendations for further understanding the bike sharing business:
1. Analyze ride start locations as well, so that typical bike route can be mapped. This will give a data-driven picture of the movement of bikes through the city.
2. Investigate birth year data to better understand the age of users. This will help to identify age groups that are under utilized to inform the marketing compaign derectives.

