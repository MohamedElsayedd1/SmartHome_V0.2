**Smart Home Project using PIC18F46K20**

**Overview:**
This repository hosts the codebase for a sophisticated Smart Home system powered by PIC18F46K20 microcontrollers. The project integrates various device drivers for EUSART, I2C, GPIO, LCD, TC74 temperature sensor, 24C01C external EEPROM, and DS1307 RTC. The master microcontroller communicates temperature data to the slave microcontroller via I2C protocol, activating an LED if the temperature exceeds 30°C. Additionally, real-time time, date, and temperature information are transmitted via the USART module.

**Components:**
- PIC18F46K20 Microcontrollers (Master and Slave)
- TC74 Temperature Sensor
- 24C01C External EEPROM
- DS1307 RTC
- LED
- LCD Display
- Various Passive Components

**Features:**
1. **Temperature Monitoring:** Continuous monitoring of temperature using the TC74 sensor.
2. **Temperature Threshold:** Automatic activation of the LED if the temperature surpasses 30°C.
3. **I2C Communication:** Transmission of temperature data from the master to the slave microcontroller via the I2C protocol.
4. **Real-time Data Transmission:** Real-time transmission of time, date, and temperature information using the USART module.

**Setup Instructions:**
1. Connect the PIC18F46K20 master and slave microcontrollers to the respective peripherals (temperature sensor, EEPROM, RTC, LED, LCD).
2. Ensure all connections are properly configured according to the schematic.
3. Upload the provided code to both the master and slave microcontrollers.
4. Power on the system and monitor the LCD display for real-time temperature updates.
5. Observe the LED activation if the temperature exceeds the predefined threshold.

**Usage:**
- Suitable for residential or commercial environments to monitor and control indoor temperature levels.
- Provides real-time temperature updates and alerts users if the temperature exceeds the predefined threshold.

**Contributing:**
Contributions to the project are welcome. Feel free to submit pull requests for bug fixes, enhancements, or additional features.

**Credits:**
- Author: Mohamed Elsayed
- Email: momaroof61@gmail.com

