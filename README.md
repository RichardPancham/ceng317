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


SparkFun Qwiic Adapter for non-qwiic sensors https://www.sparkfun.com/products/14495   
    9DoF Stick IMU - LSM9DS1   
    9DoF IMU - MPU-9250   
    6DoF IMU - LSM303C   
    6DoF IMU - LSM6DS3   
    Triple Axis Accelerometer - LIS3DH   
    Triple Axis Magnetometer - MAG3110   
    Triple Axis Magnetometer - MLX90393   
    Compass Module - HMC6343   
    Atmospheric Sensor - BME280   
    Barometric Pressure Sensor - MS5803-14BA   
    Barometric Pressure Sensor - T5403   
    Humidity and Temperature Sensor - Si7021   
    Digital Temperature Sensor - TMP102   
    Particle Sensor - MAX30105   
    Air Quality Sensor - CCS811   
    ToF Range Finder - VL6180   
    Haptic Motor Driver - DRV2605L   
    Micro OLED Display   
    RGB and Gesture Sensor - APDS-9960   
    RGB Light Sensor - ISL29125   
    LED Driver - LP55231   
    DAC Breakout - MCP4725   
    16 Output I/O Expander - SX1509   
    Battery Babysitter - BQ24075   

Past sensors/effectors:   
ADC needed for analog sensors   
Relay or drivers required for higher current draw devices, freewheeling diodes for solenoids, consider buffers for servos   
MAG3110 3-Axis Magnetometer (0x0E)   
Si4713 FM Transmitter with RDS (0x11)   
VCNL40x0 proximity sensor (0x13)   
LIS3DH 3-axis accelerometer (0x18)   
LSM303 Accelerometer & Magnetometer (0x19 for accelerometer and *0x1E for magnetometer)   
MCP9808 temp sensor (0x1A)   
MMA845x 3-axis Accelerometer (0x1C)   
LSM9DS0 9-axis IMU (0x1D for Accel/Mag, *0x6A for Gyro)   
*LSM303 Accelerometer & Magnetometer (0x19 for accelerometer and *0x1E for magnetometer)   
FXOS8700 Accelerometer/Magnetometer (0x1F)   
Chirp! Water sensor (0x20)   
FXAS21002 Gyroscope (0x21)   
MCP23008 I2C GPIO expander (0x22)   
MCP23017 I2C GPIO expander (0x23)   
VL53L0x ToF distance (0x24 software selectable)   
BNO055 IMU (0x28)   
TCS34725 color sensor (0x29)   
CAP1188 8-channel Capacitive Touch (0x2A)   
FT6x06 Capacitive Touch Driver (0x38)   
VEML6070 UV Index (0x39)   
SSD1305 monochrome OLED (0x3C)   
SSD1306 monochrome OLED (0x3D)   
HTU21D-F Humidity/Temp Sensor (0x40)   
STMPE610/STMPE811 Resistive Touch controller (0x41)   
HDC1008 Humidity/Temp sensor (0x42)   
ISL29125 Color Sensor (0x44)   
SHT31 Humidity/Temp sensor (0x45)   
TMP006 IR Temperature sensor (0x46)   
TMP007 IR Temperature sensor (0x47)   
YL-40 PCF8591 (0x48)   
TSL2561 light sensor (0x49)   
TMP102 Temperature sensor (0x4A)   
ADS1115 4-channel 16-bit ADC (0x4B)   
INA219 High-Side DC Current/Voltage sensor (0x4C)   
MB85RC I2C FRAM (0x50)   
Nintendo Nunchuck controller (0x52)   
ADXL345 3-axis accelerometer (0x53)   
MAX3010x Pulse & Oximetry sensor (0x57)   
TPA2016 I2C-controlled Amplifier (0x58)   
DRV2605 Haptic Motor Driver (0x5A)   
CCS811 VOC sensor (0x5B)   
AM2315 Humidity/Temp sensor (0x5C)   
MPR121 12-point capacitive touch sensor (0x5D)   
TEA5767 Radio receiver (0x60)   
Si5351A Clock Generator (0x61)   
MCP4725A1 12-bit DAC (0x62)   
MCP4725A2 12-bit DAC (0x64)   
MCP4725A3 12-bit DAC (0x66)   
DS3231 RTC (0x68)   
AMG8833 IR Thermal Camera Breakout (0x69)   
*LSM9DS0 9-axis IMU (0x1D for Accel/Mag, *0x6A for Gyro)   
L3GD20H gyroscope (0x6B)   
TCA9548 1-to-8 I2C Multiplexer (0x70)   
HT16K33 LED Matrix Driver (0x72)   
IS31FL3731 144-LED CharliePlex driver (0x74)   
PCA9685 16-channel PWM driver (0x75)   
MS5607/MS5611 Barometric Pressure (0x76)   
BME280 Temp/Barometric/Humidity (0x77)   
PN532 NFC/RFID reader (Use UART pins 8:TX and 10:RX)   

Consider adding: a spare header, an npn transistor and connect the LED with series 330 Ohm resistor on the collector side and the emitter to the ground, 2.2 kohm resistor between the GPIO and the base of the transistor.
