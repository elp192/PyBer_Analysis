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
- The total number of drivers is the most in rural cities (2405 drivers), about 31 and 5 times more than total drivers in rural and suburban, respectively.<br>
Figure 1 (middle) confirms the highest number of drivers in urban cities (80.9% of total drivers), whereas the lowest number in rural cities (2.6%). Also, the number of drivers is 16.5% in suburban cities.

**Total fares**<br>
- The total fares in urban cities is the highest value (about $39,800). This cost is higher than rural and suburban cities by about 4.5 and 2 times, respectively.<br>
Figure 1 (right) illustrates the highest fares in urban cities (62.7%). The lowest fares is in rural by about 6.8%. Also, the fare cost in suburban cities is approximately half of the total fare in urban cities.



<p img align="center" width="100%">
  <img width="235" alt="Total rides" src="https://user-images.githubusercontent.com/85843401/127701946-d0220eea-b74e-4792-8f2c-e068297dc435.png">
<img width="247" alt="Total drivers" src="https://user-images.githubusercontent.com/85843401/127701950-7bc844b0-bbe9-4a9d-8c30-b8cd203d154b.png">
<img width="220" alt="Total fares" src="https://user-images.githubusercontent.com/85843401/127701952-4a7a4780-8fda-4dd9-a519-36861439c7d3.png"><figcaption>Figure 1: Comparing  ridesharing criteria among different city types. Rigth) Total rides, Middle) Total drives, Left) Total fares</figcaption></figure>
</p>

