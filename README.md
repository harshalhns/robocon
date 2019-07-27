# robocon
This project contains hardware details and AVR code for manual robot that was used in Robocon 2019. 
It is based on swerve drive. Four Atmega32 controllers are responsible for turning of each wheel to a precise target angle. 
These 4 slave controllers receive commands from master Atmega2560 via SPI. 
The robot is operated using Android mobile phone. It connects to phone through ESP8266 wifi module.
