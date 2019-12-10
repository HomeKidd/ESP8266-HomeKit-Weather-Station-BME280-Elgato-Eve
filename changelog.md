**v2.1.0**
* Updated esp-homekit to the latest version
* Fixed Pressure Elevation bug _(after reboot it always returned 100m)_

**v2.0.5**

* Screen ON/OFF now happens instantly
* Fixed some UI bugs
* Bug fixes


**v2.0.4**

* Auto power off for OLED after 5 minutes to prevent screen burn-in _(on first startup the display remains powered on, but after turning on/off it enables auto power-off timer)_
* Added Characteristic for Data History _(not working yet!)_


**v2.0.3**

* Display now can be turned On/Off via single pressing a button _(GPIO0)_
* Added hidden Characteristic for Data History _(not working yet!)_
* Bug fixes

**v2.0.2**


* Display UI now shows Barometric pressure in inHg when switching to Fahrenheit
* Sensor Fault and Resetting displays on screen
* BME280 calibration _(experimenting with oversampling, data filter and standby time)_
* Bug fixes

**v2.0.1**


* Temperature Display Units characteristic for switching between Celsius/Fahrenheit display
* Display UI now shows Barometric pressure in hPA
* Bug fixes

**v2.0.0**


* Added support for SSD1306 Oled display (i2c bus, 128x64px)
* Temperature display Units characteristic for switching between Celsius/Fahrenheit display

**v1.0.4**

* Added support for LED that indicating Reset/Pairing via flashing the built-in LED
* New Name (  WeatherMonitor )
* Bug fixes

~~**v1.0.3**~~


**v1.0.2**

* Sensor Fault detection _(at the moment only with temperature)_

**v1.0.1** 

* First release
