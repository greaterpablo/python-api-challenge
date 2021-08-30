# Python-api-challenge
## What's the Weather Like?

Let's extract some data from a public API of Weather to see how it is look.

Once that we have the data, let's see what it comes.

City | Cloudiness | Country	Date | Humidity | Lat | Lng | Max Temp | Wind Speed
---- | ---------- | ------------ | -------- | --- | --- | -------- | ----------
0 | qaqortoq | 6 | GL | 1619574719 | 70 | 60.7167 | -46.0333 | 41.00	6.91
bernardino de campos | 81 | DO | 1619574719 | 77 | 18.8372 | -70.0172 | 77.00 | 1.01
yambio | 21 | SS | 1619574536 | 96 | 4.5721 | 28.3955 | 67.05 | 4.05
mataura | 100 | NZ | 1619574669 | 87 | -46.1927 | 168.8643 | 55.99 | 15.01
gimli | 5 | CA | 1619574720 | 80 | 50.6336 | -96.9907 | 35.60 | 10.36


### Part I 

Trend 1
The mean of the Humidity was 70% and cloudiness mean was 53, thats mean that if you see a lot of clouds the humidity could be high.There was no humidity over 100

![Trend1](https://github.com/greaterpablo/python-api-challenge/blob/main/WeatherPy/fig1.png) 

Trend 2
There is a breaking point between lattitude and Temperature/Humidity in which latitude 0 is a separetor in both indicators. There was no relation bewteen latitude and wind speed, nothing change changing variables.

![Trend2](https://github.com/greaterpablo/python-api-challenge/blob/main/WeatherPy/fig2.png) 

Trend 3
Hemisphere trends, north and south are inverse related in temperature and latitude, that means that the more you are close to ecuador you probabaly feel more tempearature. We can say that humidity and latitude have a space relation, as you get latitude you could feel more humidity but a certain level you provably feel nothing more.

![Trend3](https://github.com/greaterpablo/python-api-challenge/blob/main/WeatherPy/fig3.png) 

### Part II

Please follow VacationPy folder to reach Map.png to see screenshot of the heatmap.

![Map](https://github.com/greaterpablo/python-api-challenge/blob/main/VacationPy/map.png) 
