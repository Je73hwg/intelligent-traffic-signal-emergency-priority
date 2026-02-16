# Intelligent Traffic Signal Control for Emergency Vehicles

This project presents a simulation-based intelligent traffic signal control system
designed to prioritize ambulance movement at a four-way urban intersection.

## Overview
Traffic congestion often delays emergency vehicles such as ambulances.
This project simulates a rule-based traffic signal control mechanism that
temporarily overrides normal signal rotation to provide a clear path for
ambulances, thereby reducing emergency response delay.

## Approach
- Four-way intersection (North, South, East, West)
- Normal fixed-time signal rotation
- Emergency override when an ambulance is detected
- All non-emergency lanes forced to RED
- Extended GREEN phase for ambulance lane

The system is implemented as a Python simulation and executed on Google Colab.

## Key Result
- ~90% reduction in ambulance waiting time (simulation-based analysis)

## Tools Used
- Python
- Google Colab
- NumPy, Pandas, Matplotlib

## Execution
Upload the notebook to Google Colab and select:
Runtime → Run all

This project was carried out as an independent work beyond curriculum
addressing a societal and public safety issue.
