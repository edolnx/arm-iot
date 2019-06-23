# Sensor Level Code

## Purpose

The sensor nodes are traditional IoT devices, collectiong data from a series of sensors, and transmitting it to a local edge node via MQTT. The IoT nodes are Raspberry Pi 3B+ devices running arm mbed OS 5 and managed by arm Pelion.

## Sensors

 - [Sparkfun Ublox global positioning module](https://github.com/sparkfun/SparkFun_Ublox_Arduino_Library)
 - [Sparkfun AS3935 lightning detection module](https://github.com/sparkfun/SparkFun_AS3935_Lightning_Detector_Arduino_Library)
 - [Sparkfun BME280 Temp, Pressure, and Humidity module](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library)
 - [Sparkfun CCS811 TVOC and CO2 module](https://github.com/sparkfun/SparkFun_CCS811_Arduino_Library)

## TODO:

 - Port arduino sensor code to mbed 5
 - Deploy sensors
 - External enclosure?