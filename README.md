# Automatic Fan Control System

## Overview

This **Automatic Fan Control System** uses a temperature sensor to turn a fan on or off automatically, based on the surrounding temperature. The system also includes a potentiometer to set the temperature threshold for fan activation and a regulator to ensure stable power supply to the components.

## Features

- **Temperature-Based Fan Activation:** The fan turns on when the temperature exceeds the set threshold.
- **Adjustable Temperature Threshold:** A potentiometer allows you to set the activation temperature for the fan.
- **Regulated Power Supply:** A regulator ensures stable voltage for the system, enhancing reliability.
- **Simple and Efficient Design:** No complex code is involved, making it easy to build and operate.

## Components

- **Temperature Sensor:** Measures the ambient temperature.
- **Potentiometer:** Adjusts the temperature threshold for fan activation.
- **Fan:** Turns on or off based on temperature readings.
- **Regulator:** Provides stable voltage to the system.
- **Relay or Transistor:** Controls the power to the fan.
- **Microcontroller (optional):** For reading sensor data and controlling the fan.
- **Power Supply:** Powers the system components.

## Hardware Setup

1. **Connect the Temperature Sensor:**
   - Connect the sensor’s power and ground pins to the regulated power supply or microcontroller.
   - Connect the sensor’s output pin to an analog input on the microcontroller.

2. **Connect the Potentiometer:**
   - Connect one end of the potentiometer to the regulated power.
   - Connect the other end to ground.
   - Connect the wiper (middle pin) to an analog input pin on the microcontroller.

3. **Connect the Fan:**
   - Use a relay or transistor to control the fan based on the temperature readings.
   - Connect the fan to the power supply via the relay or transistor.

4. **Install the Regulator:**
   - Connect the regulator between the power source and the components (temperature sensor, potentiometer, fan) to provide a stable voltage.

5. **Optional Microcontroller Setup:**
   - If using a microcontroller, ensure it is powered by the regulated supply and programmed to handle sensor readings and control the fan.

## Usage

1. **Adjust the Threshold:** Use the potentiometer to set the desired temperature at which the fan should activate.
2. **Power the System:** Connect the power supply and ensure the regulator is providing stable voltage to the components.
3. **Automatic Fan Operation:** The fan will turn on when the temperature exceeds the threshold and turn off when it drops below the set point.

## How It Works

- The temperature sensor continuously monitors the ambient temperature.
- The potentiometer allows the user to set the activation threshold.
- A regulator ensures that all components receive stable power.
- When the measured temperature exceeds the threshold, the fan is powered on through a relay or transistor, ensuring efficient cooling.
- The fan turns off automatically once the temperature drops below the threshold.
