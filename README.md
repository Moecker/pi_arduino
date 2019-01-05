# Installation
* Have a raspberry pi with ssh connection ready (I used a Raspberry 1 Model B)
* Install arduino IDE (I used version 1.8.8) from https://www.arduino.cc/en/main/software. Use the Linux ARM version.
* scp the archive to your pi
* Clone https://github.com/sudar/Arduino-Makefile for Makefile
* The arduino does not expect any installation. (I used a Arduino Duemilanove)

# Usage
* Adapt the Makefile if needed
* make
* make upload
* make clean

# Ressources
* http://cactus.io/hookups/sensors/barometric/bme280/hookup-arduino-to-bme280-barometric-pressure-sensor
* https://github.com/adafruit/Adafruit_BME280_Library
* https://github.com/adafruit/Adafruit_Sensor
