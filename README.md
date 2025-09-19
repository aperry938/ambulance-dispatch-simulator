# Ambulance Dispatch Simulator

**Author:** Anthony Perry

A Python-based simulation to model and optimize emergency ambulance dispatch logistics based on call priority and network location.

## Project Overview

This project is a simulation of an emergency response system, designed to model and analyze the logistics of ambulance dispatch. It utilizes several datasets—representing a location network, incoming call logs, call priorities, and available ambulances—to run and test different dispatch algorithms. The prototypes (`prototype1.py`, `prototype2.py`) explore various strategies for allocating resources efficiently and minimizing response times.

This project serves as an exploration of operations research and logistical optimization using Python.

## Core Features

* **Data-Driven Simulation:** Uses real-world-style datasets (in `.csv` format) to power the simulation.
* **Algorithmic Prototyping:** Includes multiple Python scripts (`prototype1.py`, `prototype2.py`) to test and compare different dispatch strategies.
* **Resource Management:** Models a fleet of ambulances and tracks their allocation to incoming emergency calls.
* **Priority System:** Incorporates call priority levels to ensure that the most critical emergencies are handled first.

## Technologies Used

* **Python 3**
* *(You can add any specific libraries you used here, e.g., Pandas, NumPy, SimPy)*

## Datasets

The simulation is powered by the following datasets:

* `ambulance.csv`: A list of available ambulance units and their base locations or statuses.
* `calls.csv`: A log of incoming emergency calls, likely including timestamps and locations.
* `call_priority.csv`: A mapping table defining the priority level for different types of calls.
* `location_network.csv`: Defines the service area, road network, or travel times/distances between key points.

## Setup and Usage

1.  Clone the repository:
    ```bash
    git clone [https://github.com/aperry938/ambulance-dispatch-simulator.git](https://github.com/aperry938/ambulance-dispatch-simulator.git)
    cd ambulance-dispatch-simulator
    ```

2.  Ensure you have Python 3 installed. *(If you use libraries, add: `pip install -r requirements.txt`)*

3.  Run the main simulation prototype (you can update this line to point to the correct file):
    ```bash
    python prototype2.py
    ```
