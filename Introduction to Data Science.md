## This is the introduction to the data science capstone project as referred to the Coursera IBM Certified Data Associate course

# Introduction
As the introduction, through out this project , I am willing to express my problem to analysis the car accident of United States of America.
By using the dataset from Kaggle which including the accident location and types of accident's data , to cluster different reigon the place in 
America with different types of accidents to estimate the pattern of accidents distribution in America.
By using Python to plot out the map of the data and clustering the data we can using data science to have deeper understanding to the problem.

# Introduction of Data
This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is continuously being collected from February 2016, using several data providers, including two APIs which provide streaming traffic event data. This dataset consist of following data:

Description
This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is collected from February 2016 to March 2019, using several data providers, including two APIs which provide streaming traffic event data. These APIs broadcast traffic events captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 2.25 million accident records in this dataset. Check here to learn more about this dataset.

Acknowledgements
Please cite the following papers if you use this dataset:

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

Content
This data has been collected in real-time, using multiple Traffic APIs. Currently, it contains data which is collected from February 2016 to March 2019 for the Contiguous United States. Check here to learn more about this dataset.

Inspiration
US-Accidents can be used for numerous applications such as real-time accident prediction, studying accident hotspot locations, casualty analysis and extracting cause and effect rules to predict accidents, or studying the impact of precipitation or other environmental stimuli on accident occurrence.

Usage Policy and Legal Disclaimer
This dataset is being distributed only for Research purposes, under Creative Commons Attribution-Noncommercial-ShareAlike license (CC BY-NC-SA 4.0). By clicking on download button(s) below, you are agreeing to use this data only for non-commercial, research, or academic applications. You may need to cite the above papers if you use this dataset.

Data (819 MB)
Data Sources
US_Accidents_May19.csv
49 columns
About this file
This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is continuously being collected from February 2016, using several data providers, including two APIs which provide streaming traffic event data. Check here to learn more about this dataset.

Columns
IDThis is a unique identifier of the accident record.
SourceIndicates source of the accident report (i.e. the API which reported the accident.).
TMCA traffic accident may have a Traffic Message Channel (TMC) code which provides more detailed description of the event.
SeverityShows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic (i.e., short delay as a result of the accident) and 4 indicates a significant impact on traffic (i.e., long delay).
Start_TimeShows start time of the accident in local time zone.
End_TimeShows end time of the accident in local time zone.
Start_LatShows latitude in GPS coordinate of the start point.
Start_LngShows longitude in GPS coordinate of the start point.
End_LatShows latitude in GPS coordinate of the end point.
End_LngShows longitude in GPS coordinate of the end point.
Distance(mi)The length of the road extent affected by the accident.
DescriptionShows natural language description of the accident.
NumberShows the street number in address field.
StreetShows the street name in address field.
SideShows the relative side of the street (Right/Left) in address field.
CityShows the city in address field.
CountyShows the county in address field.
StateShows the state in address field.
ZipcodeShows the zipcode in address field.
CountryShows the country in address field.
TimezoneShows timezone based on the location of the accident (eastern, central, etc.).
Airport_CodeDenotes an airport-based weather station which is the closest one to location of the accident.
Weather_TimestampShows the time-stamp of weather observation record (in local time).
Temperature(F)Shows the temperature (in Fahrenheit).
Wind_Chill(F)Shows the wind chill (in Fahrenheit).
Humidity(%)Shows the humidity (in percentage).
Pressure(in)Shows the air pressure (in inches).
Visibility(mi)Shows visibility (in miles).
Wind_DirectionShows wind direction.
Wind_Speed(mph)Shows wind speed (in miles per hour).
Precipitation(in)Shows precipitation amount in inches, if there is any.
Weather_ConditionShows the weather condition (rain, snow, thunderstorm, fog, etc.)
AmenityA POI annotation which indicates presence of amenity in a nearby location.
BumpA POI annotation which indicates presence of speed bump or hump in a nearby location.
CrossingA POI annotation which indicates presence of crossing in a nearby location.
Give_WayA POI annotation which indicates presence of give_way in a nearby location.
JunctionA POI annotation which indicates presence of junction in a nearby location.
No_ExitA POI annotation which indicates presence of no_exit in a nearby location.
RailwayA POI annotation which indicates presence of railway in a nearby location.
RoundaboutA POI annotation which indicates presence of roundabout in a nearby location.
StationA POI annotation which indicates presence of station in a nearby location.
StopA POI annotation which indicates presence of stop in a nearby location.
Traffic_CalmingA POI annotation which indicates presence of traffic_calming in a nearby location.
Traffic_SignalA POI annotation which indicates presence of traffic_signal in a nearby location.
Turning_LoopA POI annotation which indicates presence of turning_loop in a nearby location.
Sunrise_SunsetShows the period of day (i.e. day or night) based on sunrise/sunset.
Civil_TwilightShows the period of day (i.e. day or night) based on civil twilight.
Nautical_TwilightShows the period of day (i.e. day or night) based on nautical twilight.
Astronomical_TwilightShows the period of day (i.e. day or night) based on astronomical twilight.
