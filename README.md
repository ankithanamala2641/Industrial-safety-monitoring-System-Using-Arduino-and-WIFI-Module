# Industrial-safety-monitoring-System-Using-Arduino-and-WIFI-Module
Overview
This project focuses on improving industrial safety by monitoring environmental conditions such as temperature and gas leakage in real time.
The system uses an Arduino Uno, sensors, and an ESP8266 Wi-Fi module to detect unsafe conditions and send alerts. When dangerous levels are detected, the system activates an alert mechanism and transmits data over the internet for remote monitoring.
This solution is low-cost, reliable, and suitable for smart industrial environments.
Features
Real-time temperature monitoring
Gas leakage detection
Automatic alert system using buzzer
Wi-Fi based notification system
Remote monitoring through internet
Low-cost IoT based industrial safety solution
Technologies Used
Hardware
Arduino Uno
Gas Sensor (MQ series)
Temperature Sensor
ESP8266 Wi-Fi Module
Buzzer
Power Supply
Software
Arduino IDE
Embedded C / Arduino Programming
IoT Communication using Wi-Fi
System Architecture
Sensors continuously monitor the environment.
Arduino processes the sensor data.
If unsafe conditions are detected:
Buzzer is activated.
Alert is sent via Wi-Fi using ESP8266.
Data can be monitored remotely through the internet.
Working Principle
The temperature sensor detects abnormal temperature levels in industrial areas.
The gas sensor identifies harmful or flammable gases.
Arduino reads the sensor data and compares it with predefined safety thresholds.
If thresholds are exceeded:
The buzzer alerts nearby workers.
The ESP8266 sends alerts to a monitoring system or smartphone.
Applications
Industrial plants
Chemical factories
Gas storage facilities
Manufacturing units
Smart factories and IoT safety systems
Advantages
Early detection of hazards
Reduces industrial accidents
Cost-effective implementation
Real-time remote monitoring
Easy to install and maintain
Future Improvements
Integration with mobile apps for alerts
Cloud data storage and analytics
Machine learning for predictive safety
Additional sensors (fire, humidity, smoke)
Project Team
M. Sahithi
N. Ankitha
Guide: Ms. K. Sumalatha
