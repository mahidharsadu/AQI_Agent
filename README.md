### Air Quality Monitoring Agent:

Group Members -  
Unnati Sai Kandimalla SE24UCSE071  
Yasaswi Inampudi SE24UCSE127  
Satya Rohit Grandhe SE24UCSE150  
Sai Mahidhar Sadu SE24UCSE156
___
### Project Overview:

This project demonstrates a Rule-Based Simple Reflex Agent that evaluates the Air Quality Index (AQI) using environmental pollutant readings. The program reads pollutant concentrations from the user and determines the corresponding air quality condition.

In Artificial Intelligence, a Simple Reflex Agent makes decisions only based on the current percept (input) and applies predefined condition–action rules. It does not store previous states or perform learning.

In this project, pollutant values act as sensor inputs, and the agent immediately maps these inputs to an AQI classification using rule conditions.
___
### Pollutants Considered:

The system analyzes four major pollutants that influence air quality:
PM2.5 – Fine particulate matter smaller than 2.5 micrometers
PM10 – Particulate matter smaller than 10 micrometers
NO₂ – Nitrogen dioxide gas from combustion sources
CO – Carbon monoxide released from vehicles and burning fuels

These pollutants are combined to estimate the overall AQI value.
___
### Air Quality Classification:

0 – 50	Clean Air  
51 – 100	Acceptable  
101 – 150	Sensitive Groups Risk  
151 – 200	Poor  
Above 200	Very Dangerous  
___
### Sample Execution:

---- Air Quality Monitoring System ----

Enter PM2.5 concentration: 70  
Enter PM10 concentration: 110  
Enter NO2 concentration: 55  
Enter CO concentration: 1.2  

Calculated AQI: 77.4
Air Condition: Acceptable
___
### Artificial Intelligence Concept Demonstrated:

This project illustrates the Simple Reflex Agent model.

Agent Components:
Sensors: Collect pollutant levels (PM2.5, PM10, NO₂, CO)
Rules: Condition-based AQI classification
Actuator/Output: Displays AQI value and air quality category

The agent operates using the rule:
IF AQI value falls in a specific range
THEN assign corresponding air quality condition

Because the decision depends only on the current input, the system represents a Simple Reflex Agent in Artificial Intelligence.
