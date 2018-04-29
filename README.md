# agri-capture

## plant data logger

**status:** ```prototype - in conception```

hardware and software for plant growers to record plant, genetic, soil, and meteorological conditions.
* intended to create datasets with correlated meteorological and plant condition data for deep-learning,
* processed deep-learning datasets will be used to predict current and historic plant conditions 

### hardware
* **digital weather station** to record plant conditions.
  * wifi-enabled
  * weather-proof enclosure for indoor and outdoor use
  
### software
* **web-user-interface** to view recorded information, charts and record plant condition / disease activity information.
* **json rest-api** interface to database 


### sensors
* carbon dioxide 
  * Adafruit SGP30 Air Quality Sensor Breakout - VOC and eCO2 https://www.adafruit.com/product/3709 - $19.95
  * Adafruit CCS811 Air Quality Sensor Breakout - VOC and eCO2 https://www.adafruit.com/product/3566 - $19.95 
* temperature, pressure, humidity 
  * Adafruit BME680 - Temperature, Humidity, Pressure and Gas Sensor https://www.adafruit.com/product/3660 - $22.50
  * Adafruit Sensiron SHT31-D Temperature & Humidity Sensor Breakout https://www.adafruit.com/product/2857
* color spectrum
  * https://www.adafruit.com/product/1334
* luminosity 
  * TSL2561 https://www.adafruit.com/product/439
* uv radiation
  * Adafruit - ANALOG UV LIGHT SENSOR BREAKOUT -https://www.adafruit.com/product/1918
* soil moisture / soil water level
  * 12" etape liquid level sensor https://www.adafruit.com/product/464
* rain guage

### connectivity
* wifi
  * ESP8266 - https://en.wikipedia.org/wiki/ESP8266
* sd card (for disconnected locations) 
* posibly 2G GPRS

### web user interface
* user interactions
  * manage weather stations
  * manage individual plants 
  * correlate plants and weather stations
* posible useful javascript components
  * https://github.com/nhnent/tui.calendar

### json rest api
* node js

### digital weather station
* teensy 3.5 / 3.6 micro-controller board
