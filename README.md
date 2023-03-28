# citi_bike_challenge

Tableau Public was utilized to create multiple visualizations for exploratory data analysis of the Citi Bike Data.

Source Data Link: https://citibikenyc.com/system-data
Source File Name: 202302-citibike-tripdata.csv.zip
Tableau Public Dashboard Link: https://public.tableau.com/app/profile/sandra.braun/viz/Citi_Bike_Top100_StarEnd_Weekdays/ClassicvsElectricBikeTypeUtilization

Special Notes: Utilized most recent data, hoping to derive most current insights available. This data has removed Age, Gender and a few other features of the data set that were previously provided. 

Data Processing: Data was ingested into a jupyter notebook and Pandas was utilzied to provide some data cleaning and restructuring. 

Visualization: Multiple visualizations were created, including Top 100 Start and End Stations for weekdays and weekend boths with the ability to toggle by day of the week. Other visualizations include an analysis of bike type (classic or electric) and ride volume, duration and membership type. Lastly, visualizations that seek out to determine if membership type has any association with the start station utilized.

The classic bikes are rented more frequently than the electric bikes. Electric bikes do tend to have a slightly slower tail drop present in the data, indicating theyre utilized slightly longer in duration on average than the classic bike types. 