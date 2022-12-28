# blynk-tasmota-controller
blynk app running on an esp8266 that controls  a tasmota sonoff device over mqtt to turn it on and off manually or with voltage thresholds

This project is a simple remote voltage monitor to allow monitoring of remote battery installations or other.
it uses blynk (legacy) as the user interface to view output from an android or apple device
it uses old code from another older project of hydroponics that parts still remain but not used any more
I have added to this code to setup voltage trigers to turn off and on a tasmota sonoff device at voltage trigers of minimum and recover voltages.
to allow turning off water pumps or other high current devices when voltage get's too low and turn back on when battary voltage recovers.
just a nodempu esp8266 is used in this project.  later I might port this to a esp32 to allow more than one input voltage to be monitored and used to triger other devices.

also we selected the ESP8266 NodeMCU 1.0 (ESP-12E Module) for this project
it is also setup to allow OTA Over The Air updates you need to setup a blynk server like I did for this project as blynk no longer supports the legacy version of blynk.
