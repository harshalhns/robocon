# robocon
This project contains hardware details and AVR code for manual robot that was used in Robocon 2019. 
It is based on swerve drive. Four Atmega32 controllers are responsible for turning of each wheel to a precise target angle. 
These 4 slave controllers receive commands from master Atmega2560 via SPI. 
The robot is operated using Android mobile phone. It connects to phone through ESP8266 wifi module.

Movement of MR1: https://drive.google.com/file/d/1RZcdZKO_QcPA8YeLSfsehZz7-IaqJbko/view?ts=5e0452a6
Passing mech: https://drive.google.com/file/d/1aKHcwnHMSf9a8_czkzGeTRfraIhykFKB/view?ts=5e0452bf
Movement of MR2: https://drive.google.com/file/d/1vg7AJLM3L7O4et1_eYZHAmFJQMHMDMgw/view?ts=5e045298
