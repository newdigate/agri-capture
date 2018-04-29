# agri-capture

## plant data logger

**status:** ```conceptual research project```

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
  * Maxim ds18s20 
  * Adafruit BME680 - Temperature, Humidity, Pressure and Gas Sensor https://www.adafruit.com/product/3660 - $22.50
  * Adafruit Sensiron SHT31-D Temperature & Humidity Sensor Breakout https://www.adafruit.com/product/2857 - $13.95
* color spectrum
  * RGB Color Sensor with IR filter and White LED - TCS34725 https://www.adafruit.com/product/1334 $7.95
* luminosity 
  * TSL2561 https://www.adafruit.com/product/439 $5.95
* uv radiation
  * Adafruit - Analog UV Light Sensor Breakout - GUVA-S12SD-https://www.adafruit.com/product/1918 $6.50
* rain guage, soil moisture, soil water level
  * Adafruit - 12" etape liquid level sensor https://www.adafruit.com/product/464 $39.95

### connectivity
* Real-time clock
  * Adalogger FeatherWing - RTC + SD Add-on https://www.adafruit.com/product/2922
* wifi
  * ESP8266 - https://en.wikipedia.org/wiki/ESP8266
    * https://www.adafruit.com/product/2821 $16.95
* sd card variant (for disconnected locations) 
  * Adafruit Feather 32u4 Adalogger https://www.adafruit.com/product/2795 $21.95
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
