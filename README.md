# Weather-Trends

Using SQL (querying and extracting the pertinent data set) and Excel (moving average calculation and data visualization: line chart) to compare the historic weather data in the whole world and in Brisbane, Australia as well as to predict the trends.

Exploring Weather Trends - Project Submission
Your submission should include:
An outline of steps taken to prepare the data to be visualized in the chart, such as:
What tools did you use for each step? (Python, SQL, Excel, etc)

I extracted the data from the database with SQL as following steps:
1- overview the CSV in city_list
![Image of city list](https://github.com/rzgarcia/Weather-trends/blob/master/1.png)

1.1- find my city Brisbane, Australia in city_list by extracting all cities in Australia to make sure the Brisbane data exists
![Image of city Brisbane](https://github.com/rzgarcia/Weather-trends/blob/master/2.png)

2- overview city_data:
![Image of city data](https://github.com/rzgarcia/Weather-trends/blob/master/3.png)

2.1- extract Brisbane weather database from city_data and download CSV:
![Image of data of Brisbane](https://github.com/rzgarcia/Weather-trends/blob/master/4.png)

3- extract Global weather database from global_data download CSV from year 1841 to 2013, because the weather data for Brisbane starts on 1841 and ends on 2013
![Image of global data](https://github.com/rzgarcia/Weather-trends/blob/master/5.png)

How did you calculate the moving average?
I did a moving average of every 20 years within Excel as following for both global and Brisbane weather.
![Image of moving average](https://github.com/rzgarcia/Weather-trends/blob/master/6.png)

What were your key considerations when deciding how to visualize the trends?
The main considerations were which data I should use and how to use them to visualize the trends.
Firstly, I observed the database and realised that the years of average temperature data for global and for Brisbane are different: global one starts from 1750 and ends with 2015, while data for Brisbane starts from 1841 and ends with 2013. I only extracted data for global temperature from 1841 to 2013, so that we only have an effective database to compare for both global and Brisbane temperature.
Secondly, I chose to use moving averages of 20 years because this method allowed me to have a better idea of the trends in time series, by ignoring some hazard fluctuations in a short term.
Finally, the line chart is a useful graph for forecasting long-term trend.

Line chart with local and global temperature trends
![Image of moving average](https://github.com/rzgarcia/Weather-trends/blob/master/7.png)

At least four observations about the similarities and/or differences in the trends
This line graph represents trends of global temperature and the temperature in Brisbane Australia following moving average of 20 years.
According to the data, the average temperature in Brisbane is always approximately 11 degrees higher than global average temperature. 
However, both of them follow the same trend and increase slowly with around 1.5 degrees from 1841 to 2013. The global average temperature went up from about 8 degrees to 9.5 degrees, while the average  temperature in Brisbane changed from around 18.5 degrees to 20 degrees. 
In conclusion, the overall upward trend of the temperature for the past 170 years tended to illustrate that people should be aware of environment issue: minimize the pollution and take good care of our unique earth.




