GSM Based Motor Control Project
About Project
This project is used to control a water pump motor using a mobile phone. The system uses an Arduino Nano, GSM module, relay module, and LCD display.
When an authorized user gives a missed call to the GSM module, the motor turns ON or OFF. The system also sends an SMS and shows the motor status on the LCD display.

Features:
- Motor ON/OFF using missed call
- Authorized mobile number checking
- SMS acknowledgement
- LCD status display
- EEPROM memory storage

Software Used:
- Arduino IDE

Programming Language:
- C++ (Arduino C/C++)

Libraries Used:
- SoftwareSerial
- EEPROM
- LiquidCrystal_I2C

Hardware Used:
- Arduino Nano (ATmega328)
- SIM800L GSM Module
- 5V Relay Module
- 16x2 LCD Display
- Water Pump Motor

Working:
This project is used to control a water pump motor using a mobile phone. When a missed call is received from the saved mobile number, the system checks the number and cuts the call automatically. If the number is correct, the motor turns ON or OFF. After the motor status changes, the system sends an SMS to the user and shows the motor status on the LCD display. The system also saves the motor status in memory. So, if the power goes off and comes back, the system can remember the last motor status. This project helps users control a water pump from a distance using a mobile phone.
