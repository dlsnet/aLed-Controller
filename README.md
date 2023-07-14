# aLed Controller

aLed Controller is an analog leds controller for the smart home. It was designed to run with Home Assistant using ESPHome and features:

-  Six analog channels. (Can control a single CCTRGB or RGBW strip, up to two RGB strips, up to three CCT strips, or up to six single color strips).
- Based on ESP32-WROOM-32.
- Runs EPSHome (or you can flash it with whatever firmware makes you happy)
- Changeable fuse
- [Optional] INA226 sensor (a current shunt and power monitor).
- [Optional] Ambient light sensor.
- [Optional] PCB temperature sensor (can be handy if you plan to run high power load).
- [Optional] SHT40 temperature and humidity sensor.
- [Optional] DS18B20 temperature sensor (cheaper, easier to get hold of, and solder compared to SHT40).
- [Optional] Outputs for up to 3 external buttons.
- [Optional] I2C bus output for plugging an external sensor.
- [Optional] Connector for ePaper display.

![aLed Controller](resources/images/PCB-Front.png)
