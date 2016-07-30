# Readme

Based on the BasicOTA example from the ESP8266 Arduino library
https://github.com/esp8266/Arduino/blob/master/libraries/ArduinoOTA/examples/BasicOTA/BasicOTA.ino

## Setup
1. Using [Platfomio](http://platformio.org/) clone and import the project.
1. Upload the sketch via serial

### Enable OTA updates

1. Enter the local IP address of the ESP8266 as the `upload_port` in [`platformio.ini`](https://github.com/jamesbowles/platform_io_ota_template/blob/master/platformio.ini)
1. The sketch will now upload via WiFi
