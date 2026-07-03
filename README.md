# urban-heat-island-monitoring
This project is an autonomous mobile environmental monitoring system developed for a laboratory at the IUT of Mulhouse to support urban climate research, particularly the study of Urban Heat Islands (UHI).

The station continuously measures air temperature, relative humidity, atmospheric pressure, air quality, and its real-time GPS position. By collecting environmental data across different urban areas, the system provides high-resolution datasets for climate and pollution analysis.

The device is designed for continuous outdoor operation. It is powered by a rechargeable 3.7 V lithium battery continuously charged by a solar panel, ensuring long-term autonomous operation with minimal maintenance.

Hardware

The system is built around an ESP32 microcontroller and includes:

ESP32 microcontroller
SHT temperature and humidity sensor
Barometric pressure sensor
Air quality sensor
GPS module
3.7 V rechargeable lithium battery
Solar panel
Mechanical Design

A custom 3D-printed enclosure was designed specifically for outdoor meteorological measurements. The enclosure provides:

Optimized ventilation for accurate ambient temperature measurements.
Efficient airflow to prevent heat accumulation around the electronic components.
Protection against outdoor environmental conditions.
A 30° solar panel tilt, optimized for the latitude of Mulhouse to improve solar energy harvesting throughout the year.
Communication

The system uses two complementary communication methods:

LoRa for long-range, low-power wireless data transmission.
Wi-Fi for local communication, database synchronization, and system configuration.
Web Platform & Database

A locally hosted web application displays all measurements in real time, including environmental data, GPS location, and system status.

When connected via Wi-Fi, sensor data are automatically transmitted to a local database for storage, visualization, and historical analysis.

Repository Contents

This GitHub repository contains all resources required to reproduce the project, including:

ESP32 source code
Web application source code
Database implementation
Electronic schematics and wiring
3D enclosure design files (STL)
Documentation and project report
System architecture and communication diagrams

This project combines embedded systems, IoT, renewable energy, wireless communication, mechanical design, database management, and web development into a complete autonomous environmental monitoring platform for scientific research and smart city applications.
