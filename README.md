Smart Home Project using PIC18F46K20

Overview:
This project showcases a sophisticated Smart Home system leveraging PIC18F46K20 microcontrollers. The system integrates various device drivers for EUSART, I2C, GPIO, LCD, TC74 temperature sensor, 24C01C external EEPROM, and DS1307 RTC. The master microcontroller communicates temperature data to the slave microcontroller via I2C protocol, activating an LED if the temperature exceeds 30°C. Additionally, real-time time, date, and temperature information are transmitted via the USART module.

Components:

PIC18F46K20 Microcontrollers (Master and Slave)
TC74 Temperature Sensor
24C01C External EEPROM
DS1307 RTC
LED
LCD Display
Various Passive Components
Features:

Temperature Monitoring: The system continuously monitors the temperature using the TC74 sensor.
Temperature Threshold: If the temperature surpasses 30°C, the LED is automatically turned on to alert users.
I2C Communication: Temperature data is transmitted from the master to the slave microcontroller via the I2C protocol.
Real-time Data Transmission: Time, date, and temperature information are transmitted in real-time using the USART module.
Setup Instructions:

Connect the PIC18F46K20 master and slave microcontrollers to the respective peripherals (temperature sensor, EEPROM, RTC, LED, LCD).
Ensure all connections are properly configured according to the schematic.
Upload the provided code to both the master and slave microcontrollers.
Power on the system and monitor the LCD display for real-time temperature updates.
Observe the LED activation if the temperature exceeds the predefined threshold.
Usage:

The system can be used in residential or commercial environments to monitor and control indoor temperature levels.
It provides real-time temperature updates and alerts users if the temperature exceeds the predefined threshold.
Contributing:
Contributions to the project are welcome. Feel free to submit pull requests for bug fixes, enhancements, or additional features.
