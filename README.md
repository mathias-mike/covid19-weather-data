## Covid Weather Data
In this project, I look to analyze the effect of weather on covid19 cases. Analysis is focused on states in the United States and daily data is collected.

#### Data
* Weather data is collected from [WeatherBit](https://api.weatherbit.io/).
* Covid data is collected from [Center for Disease Control and Prevention](https://www.cdc.gov/datastatistics/index.html)

`wrangle_act.ipynb` contains code for the wragling act done on the data, from gathering to accessing and then to cleaning. 

Cleaned transformed data is loaded into Snowflake from where is was connected to Retool and visualized on retool.

#### Analysis
[Here](https://mathiasmike.retool.com/apps/covid-weather) is a link to the Retool app with the visualization.

##### Key insight
* California has the most number of total covid 19 cases and Deaths
* An increase in temperature correlates with a decrease in number of cases and vise versa for california
* An increase in precipitation correlates with an increase in number of cases and vise versa for california
* An increase in relative humidity correlates with an increase in number of cases and vise versa for california.

