In this project I explores a vast dataset of 5,000,000+ commercial flights in 2015,
collected for the U.S. DOT Air Travel Consumer Report. Each record captures essential details like airline name, flight number, airports, flight distance, and scheduled/actual departure and arrival times.

The dataset used in the project can be accessed directly from the Maven Analytics website, 
enabling users to explore and analyze the extensive information on commercial airline flights in 2015.
https://www.mavenanalytics.io/data-playground?accessType=open&dataStructure=2lXwWbWANQgI727tVx3DRC&page=3&source=post_page-----eab86e639905

I utilizes the dataset to uncover insights into flight delays and cancellations, highlighting their implications for airlines, passengers, and industry stakeholders. By analyzing the data, valuable information can be derived to address operational challenges, 
improve customer satisfaction, and inform decision-making by airlines, regulators, and airports.

I will be conducting the analysis and visualization in Jupyter Notebook, leveraging the following imports: pandas for data manipulation, sqlite3 for SQL capabilities, matplotlib.pyplot for data visualization.
This approach allows for effective data visualization and enables data analysis using SQL and pandas functionalities.

After thoroughly examining the dataset, I have found no duplicates values.
But I found null values in Airport and Flight tables after data preprocessing.The data is clean and ready for analysis.

Number of Flights by each Airline
![Screenshot 2024-07-10 211657](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/c81492f5-b868-429c-90af-a9375ec1caac)
Southwest Airlines Co had the highest number of scheduled flights, while Virgin America had the lowest.

 Overall flight volume vary by month, By the day of the week, By the day of the Month.
 ![Screenshot 2024-07-10 212005](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/fc7426b4-0f65-4362-a039-184223b9258e)
 Based on the analysis, flights are observed to be highest in July and lowest in February, aligning with the non-leap year having fewer days. 
 Additionally, a greater number of flights were scheduled during the summer months compared to other months, indicating a seasonal trend.
The number of flights scheduled on the 31st is approximately half compared to other days, reflecting the presence of fewer months with 31 days. Additionally, there is a lower volume of flights towards the end of the month,
potentially influenced by February’s shorter duration, as well as fewer flights on weekends, particularly Saturdays.

Cancellations and Reasons
Number of canceled flights is 89884
![Screenshot 2024-07-10 213421](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/205029cb-ca9e-4aa1-89c0-c517bc073e3b),
![Screenshot 2024-07-10 213451](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/59d6c4d8-8512-4077-84d7-ba153e215e27)
Upon analyzing the data, it is evident that Southwest Airlines Co. had the highest number of canceled flights (16,043). 
However, American Eagle Airlines Inc stands out with 15,025 flight cancellations. But these cancellations involve all kinds of reasons and not just Airline/Carrier Issues.
We can see that weather stands to be the top reason for flight cancellations followed by Airline/Carrier issues.

Flight cancellation due to Airline/Carrier Issues
![Screenshot 2024-07-10 213759](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/f881236e-7251-4f4b-8622-ec7749695068)
The analysis reveals that Southwest Airlines Co. has the highest number of flights canceled due to airline issues, which aligns with its large volume of departures.
Additionally, American Eagle Airlines Inc maintains the highest cancellation rate among all airlines,
indicating a relatively higher frequency of cancellations caused by airline-related factors.

Delays and Reasons
From our analysis, it is evident that in 2015, a total of 415,513 flights experienced departure delays.
The average delay time for these flights was 9.4 minutes.
![Screenshot 2024-07-10 214059](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/f221149e-a713-459e-a9fc-25b516a73e46)
Upon further analysis, it becomes evident that Southwest Airlines Co. had the highest number of airline delays among all airlines.
Furthermore, when examining the average departure delay for flights by airline, Spirit Airlines stands out with the highest average delay time of 16 minutes, 
followed by United Air Lines Inc at 14.5 minutes.

Flight Delays due to Airline issues
![Screenshot 2024-07-10 214310](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/c1348de6-246e-4fdd-ad3a-17dac4a36a15)
Again Southwest had the highest number of delays due to airline issues and Alaska Airlines has least delay rate due to Airline Issues.

Problematic Airports
Lastly, I would like to quickly review airports that experience significant delays and cancellations.
![Screenshot 2024-07-10 214554](https://github.com/arshi-09-tech/Eda-Flight_delay_analysis/assets/128925304/1b34b8d5-6cd3-4faa-9583-dc5f5620b6cc)
 O’Hare International Airport (ORD) in Chicago holds the record for the highest count in Flight Cancellation.










