# Conductivity-sensor-analysis

## Project Overview
This project focuses on analyzing the behavior of the conductivity sensor data. This is a sensor that determines whether the condensate going to the boiler is contaminated, with values 50 us/cm it is known that the solution is contaminated, however, the room operator commented that when stopping the condensate pump the value rose, so the objective of this notebook is to determine the algorithm to implement it in the control system and that it does not throw these erroneous values.

## Objectives
- Analyze Sensor Data Trends: Identify and visualize the trends and anomalies in the conductivity sensor data to better understand its behavior under different operating conditions.
- Develop an Algorithm to Filter Erroneous Values: Create an algorithm to exclude erroneous conductivity readings caused by operational factors, such as pump stoppages.
- Provide a Solution for Control System Integration: Propose the algorithm that can be implemented in the plant's control system to ensure accurate monitoring and decision-making 
  regarding condensate contamination.
  
## Tools and Technologies
- **Programming Language**: Python
- **Library**: pandas and plotly.graph_objects
- **Data Sources**: Data from the control system (plc)

## Repository Structure
- `data/`: Contains raw data.
- `notebooks/`: Includes the Jupyter notebook with the main analysis.
- `README.md`: This file, describing the project.
