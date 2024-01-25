# IoTSmartParking
An IoT smart parking system developed using Wokwi, NODE-RED, Grafana and InfluxDB

# System Overview
This is an IoT-based Smart Parking Solution that efficiently manages parking spaces in urban areas, reduces search time for available spots, decrease traffic congestion, and provides real-time parking data to users and administrators. 

# Key Features
1. Parking spot alert: Automated update on whether there is a parking spot available whenever a driver seeks to park.
2. Dynamic Pricing: An algorithm-based pricing model to calculate fees for extended parking durations. This means that it will have a pricing feature that tells the driver what to pay if they plan on parking their car for more than the usual time.
3. Parking guidance: Automated guidance to a parking spot, if available. The system determines what type of car is trying to park and directs it to any suitable available parking spot (we are still trying to figure out how the system will determine this. One option is using a camera).
4. Electric Vehicle (EV) Priority: Automated guidance for EVs to parking spots near a charging station.
5. Data Analytics: Comprehensive analysis of parking trends, peak usage, and efficiency metrics, to enable administrators optimize parking infrastructure.

# Technology Stack
•	Sensors: IoT sensors for occupancy detection.
•	Simulators: For simulating sensor data and vehicle movements. We are considering Wowki, Tinkercard, or other simulators.
•	MQTT: For real-time messaging between sensors and the central system. We will use an MQTT broker.
•	C Program: For backend processing and logic implementation.
•	Node-RED: For creating flow-based programming and integrating various components.
•	Telegraf: An agent for collecting, processing, and transferring metrics and events.
•	Grafana: For visualizing and analyzing data.
•	InfluxDB: As a time-series database to store sensor data and analytics.
•	Docker: For containerizing the application, ensuring scalability and easy deployment.


# Requirements

Make sure you use to Compose V2 with the docker compose CLI plugin or by activating the Use Docker Compose V2 setting in Docker Desktop.

# Getting Started

Step 1: Go to the wokwi platform and run the simulations

https://wokwi.com/projects/387721428167084033

Step 2: Clone the project

git clone https://github.com/Wisdom-Kalu/IoTSmartParking.git

Step 3: Navigate to the project directory

cd IoTSmartParking

Step 4: Start the services

docker-compose up

Services can be accessed at follwing ports:

InfluxDB: http://localhost:8086/
Grafana: http://localhost:3000/
Nodered: http://localhost:1880/

Step 5: Use the provided credentials

## InfluxDB Credentials

InfluxDB: http://localhost:8086/

## InfluxDB Username: arshia

InfluxDB Password: smartParking

## Grafana Credentials

Grafana: http://localhost:3000/

Grafana Username: admin

Grafana Password: admin

Go to "Smart Parking" Dashboard in the dashboards section.


# Services Used

## WOKWI (A web-based simulation tool)
https://wokwi.com/projects/387721428167084033


