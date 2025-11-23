# Analysis-of-control-loop-improvements

## Project Overview
This project focuses on analyzing the behavior of key control variables in the priority control loops of the iodide plant. 
The data analyzed comes from field sensors, and the goal is to evaluate how these controlled variables have performed since the implementation of PID control loops.

This analysis identified key performance issues, including:
- A mismatch between input and output flows caused by a pump capacity limitation.
- Excessive variability in the Cooling Tower Inlet Temperature control loop, requiring improved tuning.
These insights have informed specific actions to optimize plant performance, such as motor upgrades for critical pumps and loop retuning to achieve greater stability.

## Objectives
- Evaluate Control Loop Performance: Analyze the behavior of the priority control loops to identify areas where tuning or design improvements are needed.
- Identify and Diagnose Operational Issues: Investigate specific events, such as mismatches between input and output flows, and determine their root causes.
- Propose Optimization Projects: Develop actionable solutions, such as pump motor upgrades and PID loop tuning, to improve control system reliability and performance.

## Tools and Technologies
- **Programming Language**: Python
- **Library**: pandas, matplotlib and plotly.graph_objs
- **Data Sources**: Data from the control system (plc)

## Repository Structure
- `data/`: Contains raw data.
- `notebooks/`: Includes the Jupyter notebook with the main analysis.
- `README.md`: This file, describing the project.

