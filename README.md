# Ride-sharing Data Analysis
## Project Overview
### Background
The Inputs Data folder includes [city_data.csv](https://github.com/elp192/PyBer_Analysis/blob/5fb9555b3de56af0cd586e701f97b13d219ea225/Inputs_Data/city_data.csv) and [ride_data.csv](https://github.com/elp192/PyBer_Analysis/blob/5fb9555b3de56af0cd586e701f97b13d219ea225/Inputs_Data/ride_data.csv) files which consist of information related to ride-sharing company (i.e., Pyber). The information about cities, type of cities (i.e., urban, suburban, and rural), ride id, fare, etc., are provided in these files. Analysis of this dataset, providing an overview of ride-sharing criteria from different city types, helps to improve business decision-making for the future.
### Purpose
The main aim of this project is to compare three different city types regarding average fare, total number of rides, total number of fares, and total number of drivers from January 2019 to May 2019.<br>
The results (Figures) are saved to the Result folder. Python (version 3.8.8) is used as the coding language, and the code is written in Jupyter Notebook. Pandas library (version 1.3.0), Numpy library (version 1.21.0), and Matplotlib library (version 3.4.2) are used to analyze the data.
## Results
The summary DataFrame (Table 1) compares ride-sharing data among rural, suburban, and urban cities from January 2019 to May 2019. In the following, the differences of ride-sharing criteria are compared for different types of city<br>
<p img align="center" width="100%">
  <img width="700" alt="Table1" src="https://user-images.githubusercontent.com/85843401/127662240-196933f4-f484-48ec-8078-1362f02df8d2.png"><figcaption>Table 1: Comparing different criteria related to ride-sharing data among different city types.</figcaption></figure>
</p>

**Total rides**<br>
- The lowest and highest number of total rides are allocated to rural cities by 125 rides and urban cities by 1625 rides, respectively.<br>
- The total number of rides in urban cities is more than in rural and suburban cities by 13 times and 2.6 times, respectively.<br>
Figure 1 (left) shows more than 2/3 (68.4%) of total rides is allocated to urban cities. However, only 26.3% and 5.3% of total rides are related to rural and suburban cities, respectively.

**Total drivers**<br>
- The total number of drivers is the most in urban cities (2405 drivers), about 31 and 5 times more than total drivers in rural and suburban, respectively.<br>
Figure 1 (middle) confirms the highest number of drivers in urban cities (80.9% of total drivers), whereas the lowest number in rural cities (2.6%). Also, the number of drivers is 16.5% in suburban cities.

**Total fares**<br>
- The total fares in urban cities is the highest value (about $39,800). This cost is higher than rural and suburban cities by about 4.5 and 2 times, respectively.<br>
Figure 1 (right) illustrates the highest fares in urban cities (62.7%). The lowest fares is in rural by about 6.8%. Also, the fare cost in suburban cities is approximately half of the total fare in urban cities.



<p img align="center" width="100%">
  <img width="235" alt="Total rides" src="https://user-images.githubusercontent.com/85843401/127701946-d0220eea-b74e-4792-8f2c-e068297dc435.png">
<img width="247" alt="Total drivers" src="https://user-images.githubusercontent.com/85843401/127701950-7bc844b0-bbe9-4a9d-8c30-b8cd203d154b.png">
<img width="220" alt="Total fares" src="https://user-images.githubusercontent.com/85843401/127701952-4a7a4780-8fda-4dd9-a519-36861439c7d3.png"><figcaption>Figure 1: Comparing  ride-sharing criteria among different city types. Rigth) Total rides, Middle) Total drives, Left) Total fares</figcaption></figure>
</p>

Overall, the correlation between average fare and the number of ride in each city type is more investigated in Figure 2. The sizes of bubbles are changed based on the driver count in each city type. From this figure, it can be seen that as the number of rides increases, the average fare decreases (negative relationship). Also, by increasing the number of drivers (bubbles size), the average fare decreases.

<p img align="center" width="100%">
   <img width="348" alt="Average fare versus total rides" src="https://user-images.githubusercontent.com/85843401/127707988-3fdb9389-2b15-4591-974b-4f6191ee0820.png"><figcaption>Figure 2: Representing the relationship between average fare and number of ride in each city type during January 2019 to May 2019.</figcaption></figure>
</p>

**Average fare per ride and driver**<br>
- On average, the passengers in rural cities and suburban cities have to pay about $34 and $30 respectively per ride. However, passengers in urban cities pay $6-10 less than other city types ($24.5).<br>
- On average, the drivers in rural cities and suburban cities receive $55.5 and $39.5, respectively. However, drivers in urban cities receive $16.5.

**Weekly total fare in each city type**<br>
- Figure 3 shows the average of fare cost from January 2019 to May 2019. In all months, the total fare cost in rural cities is less than in suburban and urban cities.<br>
- In the rural cities with the lowest total fares compared to other city types, the range of fare cost is about $50 to $500. In these cities, the highest fare cost is at the beginning of April (about $500), and the lowest fare cost is at the beginning of January.<br>
- In suburban cities, the difference between the lowest and highest fare is about $600. In these cities, the highest fare is at the end of February (about $1400), and the lowest fare is at the beginning of January and middle of April (about $800).<br>
- In urban cities with the highest fare, the fare is changed from $1700 to $2500. In these cities, the lowest fare is at the beginning of January, and the highest fare is at the end of February and beginning of March.<br>
- There is not significant fluctuation regarding average of fares in different city types during months. 

<p img align="center" width="100%">                                            
    <img width="512" alt="Fig 8" src="https://user-images.githubusercontent.com/85843401/127676690-003d3303-ae8a-42e8-8bd7-db8bb38d49d6.png"><figcaption>Figure 3: Comparing total fare in each type of city during January 2019 to May 2019.</figcaption></figure>
</p>

:white_check_mark: Overall, total rides in urban cities is more than other types. The reason can be the lower cost of fare for passengers in urban cities. Rural cities with the highest fare cost by per ride is the better choice for those wants to be a driver.

## Summary
Analysis of ride-sharing data shows that there are disparities among different city types in this market. There are some recommendations to tackle the disparities.<br>
:white_small_square: The number of drivers and rides in rural cities are low, and the average fare per ride and driver is very high. Increasing the share-riding services resulting in an increasing number of rides and drivers, may help decrease the fare per ride and improve this market. However, before providing more drivers, some essential factors such as the demand for using Pyber service, the population of urban cities, distance of travel, etc need to be studied.<br>
:white_small_square: One of the reasons for fewer rides in rural cities can be the inaccessibility of people to Pyber services. Studies need to be done to make sure all people in these areas have access to this service.<br>
:white_small_square: In each type of city, the peak of fare cost occurs in specific months of the year. The reasons for increasing the fare in these months need to be determined. For example, if the reason is increasing the demand, hiring more drivers can help to decrease the fare.<br>
