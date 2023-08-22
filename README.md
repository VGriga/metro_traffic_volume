# 🚇Metro Traffic Volume prediction🚇
Abstract: Hourly Minneapolis-St Paul, MN traffic volume for westbound I-94. Includes weather and holiday features from 2012-2018. 
https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume
## 🐕Features🐕
| Feature | dtype | Description |
| --- | --- | --- |
holiday                |Categorical|    US National holidays plus regional holiday, Minnesota State Fair
temp                   |Numeric      |  Average temp in kelvin
rain_1h                |Numeric     |   Amount in mm of rain that occurred in the hour
snow_1h                |Numeric       | Amount in mm of snow that occurred in the hour
clouds_all             |Numeric        |Percentage of cloud cover
weather_main           |Categorical    |Short textual description of the current weather
weather_description    |Categorical    |Longer textual description of the current weather
date_time              |DateTime       |Hour of the data collected in local CST time
traffic_volume         |Numeric        |Hourly I-94 ATR 301 reported westbound traffic volume

## 🤖Models used best score🤖
| Model | features selection | R2 |
| --- | --- | --- |
Decision Tree Regressor | False | 0.930
Random Forest Regressor | False | 0.946
K Nearest Neighbors Regressor | Lasso | 0.919
Lasso | Lasso | 0.835
Ridge | Lasso | 0.835

