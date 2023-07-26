# project-1 - 
## Uber rides trends in New York city

## Project Overview: 
The Uber Rides trends data analytics project aims to analyze and visualize data collected from Uber rides in New York City to gain insight into rider patterns, popular routes, and overall ride trends.

## Questions:
We performed the analysis by working on the following questions.

1. Which is the `destination` with the most rides?
`Motivation`: we wanted to understand what hours of the day are the peak requests ad which city has the most uber requests.
What are the earnings of Uber drivers based on factors such as time of day, location, or type of vehicle used?
Also,we wanted to find if there is a relation between public transportation line and uber pickup and dropoff location? 

2. What is the average `fare` amount?
`Motivation`: We were curious about how a driver can get data into which area has the highest fares. Basically, do Uber Fares depend on different times of the day and duration of the ride?
	
3. Does `weather` affect transportation and traffic?
Motivation: we wanted to get a sense of distribution of rides by weather conditions and if there is a correlation between weather and rides.

## How and where we found the data? 

### We use Uber ride data from Kaggle, for New York City, from 2009 to 2015. [https://www.kaggle.com/datasets/yasserh/uber-fares-dataset]

### Openweather - We use a historical data set from Openweather where we could find the New York weather from 2009 ti 2015.

If you want to review the data set, you will find it in a folder called `Resources`; the file will be called `openweather 2009 2015.csv`.

### New York City Subway lines data from Government website

### Geoapify.com - for visualization of subway destinations and drop off locations

## Analysis

You will find a .ipynb file (project1-Group3.ipynb) where the code is developed to obtain the answer to each question posed.

Below you will find the results we obtained in our project:

### Which is the `destination` with the most rides?

#### What hours of the day are the peak requests?

xxxxxx

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/6_peak_requests.png)

#### Zone with the highest requests in the request peak hour.

xxxxxx

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/7_zone_highest_peak_request.png)



### What is the average `fare` amount?

#### Top 5 zone with the best earning by ride

xxxxx

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/8_top5_zone_best_earning.png)


#### Is there price surge in relation to time of the day, rush hour or weather?

xxxxxx

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/3_average_fare_amount_by_weather.png)

xxxxxx

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/5_average_numberof_rides_by_weather.png)

### Does `weather` affect transportation and traffic?

#### Correlation between Rides & Temperature

In this section we can see the relationship between number of rides and temperature, both in the New York Area.

An r-value of 0.1026 indicates a very weak correlation between these two variables in NY. The value close to zero suggests that there is no significant linear relationship between them in the analyzed data.

However, as you can see, the graph shows a bell between rides and temperature, with the majority of data concentrate around the central data and then gradually decreasing to the sides. 

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/1_correlation.png)

#### Do people avoid rides on sunny days ?

xxxx

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/5_average_numberof_rides_by_weather.png)


#### Number of rides by day of week

The bar chart shows the frequency of Uber trips taken on different days of the week. On the horizontal axis (x axis), are the days of the week: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, and Sunday. The vertical axis (y-axis) represents the number of Uber trips made each day.

With the results of the exercise, we see that the bars for Friday and Saturday are significantly higher than the other bars, indicating that people tend to use Uber more on weekends. This may be because people go out more, go to parties, social events or do leisure activities during these days.

On the other hand, we note that the bar corresponding to Monday is the lowest of all, which suggests that it is the day of the week when Uber is used the least. This decrease could be due to the fact that many workers prefer to use means of transport, such as public transport or their own car, to go to their workplaces at the beginning of the week.

![alt text](https://github.com/KevinZhuangC/project-1/blob/main/output_data/4_number_rides_by_day.png)

### Resource: 

En la carpeta `Recursos` encontrara las bases de datos con la que construimos nuestro proyecto.

`openweather_2009_2015.csv`
`uber.csv`

### Output Data:

In this folder, you will find the graphs obtained from the analyzed data.

`data_complete.csv`
`1_correlation.png`
`2_average_fare_amount_by_hour.png`
`3_average_fare_amount_by_weather.png`
`4_number_rides_by_day.png`
`5_average_numberof_rides_by_weather.png`
`6_peak_requests.png`
`7_zone_highest_peak_request.png`
`8_top5_zone_best_earning.png`


PPT: 

You will find a PowerPoint presentation of the project.





