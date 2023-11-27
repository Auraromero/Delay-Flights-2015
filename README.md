
Project Overview:

In this project, I am gonna be analyzing a dataset containing information about flight delays. The primary focus is on understanding the patterns and factors associated with departure delays in domestic flights. The dataset covers the year 2015 and includes various features such as airline information, departure and arrival times, reasons for delays, and cancellation details.

Key steps in the project include:

1. Data Exploration:
   - We started by exploring the dataset to understand its structure and contents.
   - Examined columns related to flight details, dates, airlines, and reasons for delays.

2. Data Cleaning:
   - Identified and handled missing values to ensure the accuracy of our analysis.
   - Checked for and addressed any inconsistencies or anomalies in the data.

3. Feature Engineering:
   - Created relevant features to enhance our analysis, such as the day of the week and month.
   - Calculated metrics like average departure delay by airline to gain insights.

4. Data Analysis:
   - Conducted exploratory data analysis to identify trends, patterns, and outliers.
   - Visualized the data using plots and graphs to facilitate interpretation.

5. Insights and Visualization:
   - Generated visualizations to highlight the average departure delay by airline.
   - Explored on-time departure percentages to evaluate airline reliability.

6. Conclusion:
   - Derived conclusions and insights about the most and least reliable airlines regarding on-time departures.
   - Provided visual representations to enhance the understanding of the findings.

7. Future Considerations:
   - Considered potential avenues for further analysis or improvements.
   - Discussed possible recommendations for stakeholders based on the insights gained.

Through these steps, I aim to provide a comprehensive overview of departure delays in domestic flights during the specified period and offer valuable insights for both industry stakeholders and passengers.





Flight Dataset Overview:

The dataset contains information about flights in the year 2015, providing a comprehensive view of air travel during that period. Here are key aspects of the dataset:

 Temporal Coverage:
  - Data spans the entire year of 2015.
  - Includes details on flights each month, day, and day of the week.

Airline Information:
  - Specifies the airline associated with each flight.
  - Enables the analysis of individual airline performance.

Flight Operations:
  - Covers departure and arrival times.
  - Includes departure and arrival delays, aiding in understanding punctuality.

Cancellation Details:
  - Identifies reasons for cancellations (if any).
  - Allows analysis of the frequency and causes of flight cancellations.

Aircraft Specifics:
  - Provides information on flight numbers, tail numbers, and origin/destination airports.
  - Useful for tracking specific flights and understanding route patterns.

Delay Breakdown:
  - Differentiates delays into categories like air system, security, airline, etc.
  - Facilitates a granular analysis of the reasons behind delays.

Weather Impact:
  - Indicates delays caused by weather conditions.
  - Useful for assessing the influence of weather on flight schedules.

Flight Status:
  - Distinguishes between on-time departures and delayed departures.
  - Supports the evaluation of overall flight punctuality.

This dataset is valuable for exploring trends, identifying performance metrics for airlines, and understanding the factors contributing to delays and cancellations in the aviation industry during 2015.


Questions:

How does the overall flight volume vary by month? By day of the week?

![flight_volume_by_month](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/a18ea8a4-b781-4014-b582-97bcdae10645)


 
It seems to be that the busiest months of the year for air travel are  March, July, August, and September with over 500K passengers each month. This is due to the long Holidays/vacations (spring break,  summer).  The month with fewer travelers in May, the rest of the year is very consistent with over 450K travelers per month.

 ![flight_volume_by_day](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/62584e86-0b93-4401-b8c6-d8d398ef2472)



The day of the week that has less air traffic is Thursday with a volume of 700K passengers, the rest of the week is pretty consistent with a volume of passengers of over 800K.

What percentage of flights experienced a departure delay in 2015? Among those flights, what was the average delay time, in minutes?

The year 2015 had a total volume of 5,819,079 flights, from which  36.53% (2,125,709) experienced delay with an average delay time of 32.67 minutes. This means that more than ⅓ of flights had delay issues

How does the % of delayed flights vary throughout the year? 

![perce-delay_flights_bymonth](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/f48827d4-14f0-4af5-9262-3f39280dba6a)

 
The biggest percentage of delayed flights happens to be just when the Summer vacation starts, June, and as the graphic represents the months with a percentage of delayed flights equal to or greater than 40% are December, February, Jun, and July. The most with a minimum percentage of delays are September, October, November, and April.

What about flights leaving from Boston (BOS) specifically?

![perce_delay_flights_from_boston](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/c8af89a9-1e91-4f7e-ac5e-1553e65fd53a)

 
It is interesting that Flight delays from Boston are at their peak in February, according to records, in 2015 February temperature happened to be below average due to a cold Wave. for that month the average temperature in Boston was 19.0 F, making it the second-coldest month of all-time (behind February 1934). The rest of the year has percentages below 40%, and the Holiday season has the highest percentage of delay.

How many flights were canceled in 2015?

![percentage_flight_cancellation_byreason](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/72c01a05-382c-4f6c-ae1e-7ff21bbab5b8)

In 2015 the total number of flights that were canceled was 89884, from those around 54.35% (48851) were canceled due to weather conditions and, 28.11% (25266) due to airline/carrier reasons.
Here is a more visual representation analysis of what were the reasons for flight cancellations and their percentages. Weather is definitely the biggest factor, followed but the Airline/Carrier and, National Air System. 
 
Which airlines seem to be the most and least reliable regarding on-time departure?

![percentage_ontime_dep_byairline](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/08aa4d53-17f9-4dbd-9494-db80b1cdca7f)

There are several reasons for airlines to delay flights, the biggest one being Weather. According to the analysis, UA (United Airlines) seems to be the less reliable airline when it comes to on-time departure with only 50.25%, followed by WN (Southwest Airlines) and, NK (Spirit Airlines). The three most reliable airlines based on the percentage of on-time departures are AS (Alaska Airlines) with 74.75%, HA (Hawaiian Airlines) with 73.59%, and OO (Skywest Airlines) with 70.84%. 
The volume of delay flights per airline gives them the ability to be reliable or not, and at the same time the average time (min) of delay flights gives a deper  inside on reliability. 
 
![Average_departure_delay_by_airlinep](https://github.com/Auraromero/Delay-Flights-2015/assets/121949949/f88b4bd1-66f5-4c94-8132-0a88cd40d07e)


Conclusions:
●	The flight volume varies by month, with some months experiencing higher traffic than others. The highest volume is typically observed during peak travel seasons.

●	A certain percentage of flights experienced departure delays in 2015. The percentage varies throughout the year, indicating potential seasonal factors affecting delays.

●	Among the delayed flights, the average departure delay time in minutes was calculated. This metric helps in understanding the typical extent of delays for the affected flights.

●	The reliability of airlines was assessed based on their on-time departure performance. Some airlines consistently demonstrated higher on-time departure rates, while others had lower rates.
●	The analysis also included the calculation of the monthly volume of flights. This provides insights into the distribution of flight activity over the months of the year.

●	 The daily flight volume was examined to identify patterns and variations in flight activity based on the day of the week.

●	The dataset includes information on flight cancellations, and further analysis can be conducted to determine the most common reasons for cancellations, such as weather, airline-related issues, or other factors.

For a more granular understanding, airport-specific analyses can be performed, focusing on departure and arrival delays at specific airports.
Overall, the analysis provides valuable insights into the factors influencing flight delays, the performance of airlines, and the temporal patterns of flight activity. Further investigation into specific reasons for delays and cancellations can contribute to targeted improvements in the aviation industry.



The data set can be found in this website: https://mavenanalytics.io/data-playground?order=-fields.dateUpdated&search=delay

