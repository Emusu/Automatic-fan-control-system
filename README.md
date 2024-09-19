
# Automatic Fan Control System Simulation

## Overview

This **Automatic Fan Control System** is a simulation project designed in **Proteus**. It uses a temperature sensor to automatically control a fan based on the ambient temperature. The potentiometer allows adjustment of the temperature threshold for fan activation, while a regulator ensures stable power within the simulation.

## Features

- **Temperature-Based Fan Activation:** The fan is activated automatically when the temperature exceeds the threshold.
- **Adjustable Temperature Threshold:** A potentiometer lets the user set the temperature at which the fan turns on.
- **Regulated Power Supply:** A regulator ensures stable voltage in the simulation, enhancing system reliability.
- **Simulation in Proteus:** The entire system is simulated, demonstrating how it would function in a real-world scenario.

## Components (Proteus Simulation)

- **Temperature Sensor (Simulated):** Monitors the simulated ambient temperature.
- **Potentiometer (Simulated):** Adjusts the temperature threshold.
- **Fan (Simulated):** Operates when the temperature exceeds the threshold.
- **Regulator (Simulated):** Ensures stable voltage in the system.
- **Relay or Transistor (Simulated):** Controls the fan's power based on temperature.
- **Microcontroller (Optional, Simulated):** Simulates reading sensor data and controlling the fan.
- **Power Supply (Simulated):** Provides stable power in the simulation.

## Simulation Setup in Proteus

1. **Import Components:**
   - Add the temperature sensor, potentiometer, fan, and regulator to your Proteus simulation workspace.
   
2. **Connect the Temperature Sensor:**
   - Wire the sensor's power and ground to the regulated power supply.
   - Connect the sensor's output to the input (analog or digital) of the controlling element.

3. **Connect the Potentiometer:**
   - Wire the potentiometer to the power and ground in the simulation.
   - Connect its wiper (middle pin) to the input for threshold adjustment.

4. **Connect the Fan:**
   - Use a relay or transistor to control the fan’s operation.
   - Wire the fan to the power supply and the control element.

5. **Regulator Connection:**
   - Ensure the regulator provides stable voltage to all components in the simulation.

6. **Simulate the System:**
   - Run the simulation and adjust the potentiometer to change the fan's activation temperature.

## Usage

1. **Open the Simulation in Proteus:**
   - Load the `.pdsprj` file in Proteus.
   
2. **Run the Simulation:**
   - Start the simulation and observe how the system reacts to temperature changes.
   
3. **Adjust the Threshold:**
   - Use the potentiometer to modify the activation threshold for the fan.

## How It Works

- The temperature sensor continuously monitors the simulated environment.
- The potentiometer allows adjustment of the temperature threshold.
- The regulator ensures stable voltage in the simulation.
- Once the temperature exceeds the set threshold, the fan is activated through the relay or transistor.
- The system automatically turns off the fan when the temperature falls below the threshold.
