# CENG 317 First Class Fall 2023 Submission Sheet

| Student name:                       |           |
|-------------------------------------|-----------|	
|CENG 317 Hardware Project            |           |
| Section Letter Code:                |   B       |
|CENG 322 Software Project            |           |
| Semester enrolled:                  |           |
| Section Letter Code:                |           |
|Project choice on bb discussion board|           |
Sheets will be collected at 4pm you can continue to make your decision for the rest of this week:	

Possible choices:   
https://www.sparkfun.com/categories/tags/qwiic-imaging   
https://www.sparkfun.com/categories/tags/qwiic-distance   
https://www.sparkfun.com/categories/tags/qwiic-movement   
https://www.sparkfun.com/categories/tags/qwiic-environmental   
https://www.sparkfun.com/categories/tags/qwiic-other   
In addition to power and ground the sense hat uses:   
pin 3 -- GPIO2 or SDA   
pin 5 -- GPIO3 or SCL   
pin 16 -- GPIO23 (IMU Interrupt)   
pin 18 -- GPIO24 (IMU Interrupt)   
pin 22 -- GPIO25 (Atmel Prog Reset)   
pin 24 -- GPIO8 (Atmel Chip Reset)   
pin 27 -- GPIO0 (or maybe ID_SD or maybe EEPROM SDA or maybe HAT ID)   
pin 28 -- GPIO1 (or maybe ID_SC or maybe EEPROM SCL or maybe HAT ID)   
LED2472G connected via an Atmel ATTINY88 (0x46)   
LSM9DS1 IMU magnetometer 0x1c(0x1e) and accelerometer/gyroscope 0x6a(0x6b)   
LPS25H Pressure/Temperature sensor (0x5c)   
HTS221 Humidity/Temperature sensor (0x5f)   
When choosing a sensor/effector Consider your interest, cost, the I2C address, for example:   
https://www.sparkfun.com/categories/tags/qwiic-gps   
0x10 XA1110 GPS Breakout, not a good choice since we don't have access to a solid GPS signal in the classroom.   
