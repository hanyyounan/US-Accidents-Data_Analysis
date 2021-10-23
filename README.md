#  US ACCIDENTS Data 
<b>A Countrywide Traffic Accident Dataset (2016 - 2020)</b>

### <i>By Hany Y Wasef</i>
<hr></hr>

## DataSet
>Reducing traffic accidents is an essential public safety challenge all over
the world; therefore, accident analysis has been a subject of much research in
recent decades.<br>
>In This project I will focus a countrywide traffic accident dataset, which covers 49 states of the United States. 
>The accident data are collected from February 2016 to Dec 2020, using multiple APIs that provide streaming traffic incident (or event) data. 
>These APIs broadcast traffic data captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. 
>Currently, there are about 5000 accident records in this dataset.
<hr></hr>

## DataSet Description
There are 5000 records in this dataset from February 2016 to December 2020 with 47 features that represent:
<ol>
    <li><b>ID</b> :</li> This is a unique identifier of the accident record.
    
<hr></hr>
<li><b>Severity</b> :</li> Shows the severity of the accident, a number between 1 and 4, where 1 indicates the least impact on traffic and 4 indicates a significant impact on traffic.

<hr></hr>
<li><b>Start_Time</b> :</li> Shows start time of the accident in local time zone.

<hr></hr>
<li><b>End_Time</b> :</li> Shows end time of the accident in local time zone. End time here refers to when the impact of accident on traffic flow was dismissed.

<hr></hr>
<li><b>Start_Lat</b> :</li> Shows latitude in GPS coordinate of the start point.

<hr></hr>
<li><b>Start_Lng</b> :</li> Shows longitude in GPS coordinate of the start point.

<hr></hr>
<li><b>End_Lat</b> :</li> 	Shows latitude in GPS coordinate of the end point.
<hr></hr>
<li><b>End_Lng</b> :</li> Shows longitude in GPS coordinate of the end point.
<hr></hr>
<li><b>Distance(mi)</b> :</li> The length of the road extent affected by the accident.
<hr></hr>
<li><b>Description</b> :</li> Shows natural language description of the accident.
<hr></hr>
<li><b>Number</b> :</li> 	Shows the street number in address field.
<hr></hr>
<li><b>Street</b> :</li>	Shows the street name in address field.
<hr></hr>
<li><b>Side</b> :</li>	Shows the relative side of the street (Right/Left) in address field.
<hr></hr>
<li><b>City</b> :</li>	Shows the city in address field.
<hr></hr>
<li><b>County</b> :</li>	Shows the county in address field.
<hr></hr>
<li><b>State.</b> :</li> 	Shows the state in address field
<hr></hr>
<li><b>Zipcode</b> :</li> 	Shows the zipcode in address field.
<hr></hr>
<li><b>Country</b> :</li>	Shows the country in address field.

<hr></hr>
<li><b>Timezone</b> :</li>	Shows timezone based on the location of the accident (eastern, central, etc.).

<hr></hr>
<li><b>Airport_Code</b> :</li>	Denotes an airport-based weather station which is the closest one to location of the accident.

<hr></hr>
<li><b>Weather_Timestamp</b> :</li>	Shows the time-stamp of weather observation record (in local time).

<hr></hr>
<li><b>Temperature(F)</b> :</li>	Shows the temperature (in Fahrenheit).

<hr></hr>
<li><b>Wind_Chill(F)</b> :</li>	Shows the wind chill (in Fahrenheit).

<hr></hr>
<li><b>Humidity(%)</b> :</li>	Shows the humidity (in percentage).

<hr></hr>
<li><b>Pressure(in)</b> :</li>	Shows the air pressure (in inches).

<hr></hr>
<li><b>Visibility(mi)</b> :</li>	Shows visibility (in miles).

<hr></hr>
<li><b>	Wind_Direction</b> :</li>	Shows wind direction.

<hr></hr>
<li><b>Wind_Speed(mph)</b> :</li>	Shows wind speed (in miles per hour).

<hr></hr>
<li><b>Precipitation(in)</b> :</li>	Shows precipitation amount in inches, if there is any.

<hr></hr>
<li><b>Weather_Condition</b> :</li>	Shows the weather condition (rain, snow, thunderstorm, fog, etc.)

<hr></hr>
<li><b>Amenity</b> :</li>	A POI annotation which indicates presence of amenity in a nearby location.

<hr></hr>
<li><b>Bump</b> :</li>	A POI annotation which indicates presence of speed bump or hump in a nearby location.

<hr></hr>
<li><b>Crossing</b> :</li>	A POI annotation which indicates presence of crossing in a nearby location.

<hr></hr>
<li><b>Give_Way</b> :</li>	A POI annotation which indicates presence of give_way in a nearby location.

<hr></hr>
<li><b>Junction</b> :</li>	A POI annotation which indicates presence of junction in a nearby location.

<hr></hr>
<li><b>No_Exit</b> :</li>	A POI annotation which indicates presence of no_exit in a nearby location.

<hr></hr>
<li><b>Railway</b> :</li>	A POI annotation which indicates presence of railway in a nearby location.

<hr></hr>
<li><b>Roundabout</b> :</li>	A POI annotation which indicates presence of roundabout in a nearby location.

<hr></hr>
<li><b>Station</b> :</li>	A POI annotation which indicates presence of station in a nearby location.

<hr></hr>
<li><b>Stop</b> :</li>	A POI annotation which indicates presence of stop in a nearby location.

<hr></hr>
<li><b>Traffic_Calming</b> :</li>	A POI annotation which indicates presence of traffic_calming in a nearby location.

<hr></hr>
<li><b>Traffic_Signal</b> :</li>	A POI annotation which indicates presence of traffic_signal in a nearby loction.

<hr></hr>
<li><b>Turning_Loop</b> :</li>	A POI annotation which indicates presence of turning_loop in a nearby location.

<hr></hr>
<li><b>Sunrise_Sunset</b> :</li>	Shows the period of day (i.e. day or night) based on sunrise/sunset.

<hr></hr>
<li><b>Civil_Twilight</b> :</li>	Shows the period of day (i.e. day or night) based on civil twilight.

<hr></hr>
<li><b>Nautical_Twilight</b> :</li>	Shows the period of day (i.e. day or night) based on nautical twilight.

<hr></hr>
<li><b>Astronomical_Twilight</b> :</li>	Shows the period of day (i.e. day or night) based on astronomical twilight.

</ol>

##### I will create new columns for :

- Year (start_year)
- Month (start_month)
- Hour (start_hour)
- Day (start_day)

<hr></hr>

## Summary of Findings
<hr></hr>

### My Questions
<ul>
    <li><b>What is the severity of these accidents?</b></li>
        <ul>
            <li>In previous chart  Severity indicates the impact of the accident.</li>
            <li>Severity 3,4 having a high impact.</li>
            <li>Severity 2 accidents are most impact.while Severity 1 accidents are least impact</li>
        </ul>
    <li><b>What is the percentage of accidents in each timezone?</b></li>
        <ul>
            <li>The pie chart shows that the Eastern Time zone having the highest number of accidents around 41% than pacific, central, and                        Mountain time zone.</li>
        </ul>
    <li><b>What is the number of accident in each year?</b></li>
        <ul>
            <li>The previous chart indicates that the Number of Accidents were lower and showed a more significant change in the early years as                   compared with those in recent years when the number of accidents has been raised high.</li>
        </ul>
    <li><b>what is The Trend of Accidents by Month?</b></li>
        <ul>
            <li>Monthly accidents increase steadily from the lowest points in January and February, and decrease again in Jully, peak in October-                 November-December. First half showing a smaller number of accidents compared to the second half of the year. Monthly accident                     rates steadily increase from the lowest points in February, and peak in the last quarter of the year.</li>
        </ul>
    <li><b>What is The Trend of Accidents by Day?</b></li>
        <ul>
            <li>There is a large number of accidents during weekdays (Monday to Friday). On the contrary, there are relatively fewer accidents on                 weekends (Saturday, and Sunday).</li>
        </ul>
    <li><b>What is The Trend of Accidents by Hour?</b></li>
        <ul>
            <li>Peak hours of the accidents are 7 AM, 8 AM, 5 PM, and 6 PM. while night time (10 PM-5 AM) is the safest time to travel which is                    showing less number of accidents.</li>
        </ul>
    <li><b>In which period of day has more accidents?</b></li>
        <ul>
            <li>It is clear that the day period has more accidents than the night period.</li>
        </ul>
    <li><b>What is The Relationship of the Accident between the Various Factors?</b></li>
        <ul>
            <li>The heatmap showing The accident correlation matrix between various factors. From the matrix, for accident Start Lat and End Lat                  are the crucial factors for the accident. Temp and wind flow are playing an important role.</li>
        </ul>
</ul>
