### Sample MVP

Presentation Link: https://app.box.com/s/8jrqjszmkqljkc9q4iac4myrpiyk6azg

Code link: https://github.com/a2mm-iot-hackathon/iot-samples/blob/master/temp-hum-logger.ino

temp-hum-logger:
This code collects temperature and humidity data from the sensor and logs it on adafruit.io.
Dashboard Link - https://io.adafruit.com/YOCX/dashboards/temphummon

![Architecture Tech stack](https://github.com/iot-maker1/TempHumMonMVP/blob/main/arch.jpg)

![Temp-Hum-setup](https://github.com/iot-maker1/TempHumMonMVP/blob/main/Argon-temphum-mon.jpg)

![Temp-Hum-dash](https://github.com/iot-maker1/TempHumMonMVP/blob/main/argon-adafruit-io.jpg)

It also checks for a condition of humidity too-high. This event is then used by IFTTT to send a notification SMS text.

![Temp-Hum-IFTTT](https://github.com/iot-maker1/TempHumMonMVP/blob/main/IFTTT-Applet.jpg)


