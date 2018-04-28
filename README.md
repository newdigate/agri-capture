# agri-capture

```status: prototype; in conception;```

a data logger and software for plant growers to record plant, soil, and meteorological conditions.
* intended to create datasets with correlated meteorological and plant condition data for deep-learning,
* processed deep-learning datasets will be used to predict current and historic plant conditions 

## project breakdown
  * **digital weather station** to record weather conditions for indoor and outdoor plant growers.
    * wifi-enabled
    * weather-proof enclosure for indoor and outdoor use
  * **web-user-interface** to view weather charts and record disease activity information.
  * **json rest-api** interface to database 

## sensors
* carbon dioxide 
* temperature
* pressure
* relative humidity
* luminosity / radiation
* soil moisture
* rain guage

## connectivity
* wifi
  * ESP8266 - https://en.wikipedia.org/wiki/ESP8266
* sd card (for disconnected locations) 
* posibly 2G GPRS

# web user interface
* https://github.com/nhnent/tui.calendar

# json rest api
* node js

# digital weather station
* teensy 3.5 / 3.6 micro-controller board
