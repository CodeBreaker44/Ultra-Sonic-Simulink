# Ultrasonic Distance Measurement Simulink Model

## Overview
This Simulink model simulates an ultrasonic sensor system for distance measurement. The model is built from scratch without using the built-in ultrasonic sensor block. The calculated distance is then displayed on a simulated 7-segment display.

## Model Components
- **Ultrasonic Signal Emitter**: Generates the ultrasonic signal.
- **Signal Receiver**: Simulates the reception of the ultrasonic signal after bouncing off an object.
- **Signal Processing Subsystem**: Calculates the time it takes for the signal to return and converts it into a distance measurement.
- **7-Segment Display Decoder**: Converts the distance measurement into a format that can be displayed on the 7-segment display.
- **7-Segment Display**: Shows the distance measured by the ultrasonic system.

## Prerequisites
- MATLAB
- Simulink
- Stateflow (for state-based components, if any)
- DSP System Toolbox (for signal processing components, if any)

## Setup Instructions
1. Clone the repository or download the `.slx` file to your local machine.
2. Open MATLAB and navigate to the directory containing the `.slx` file.
3. Open the Simulink model by double-clicking the file or by using the `open` command in MATLAB Command Window.
4. Ensure all required toolboxes are installed.

## Running the Simulation
1. After opening the model, configure the simulation parameters as needed.
2. Press the 'Run' button in the Simulink toolbar to start the simulation.
3. Observe the distance measurements on the simulated 7-segment display within the Simulink model.

## Customization
- The model parameters can be adjusted to simulate different ultrasonic sensor characteristics.
- The display subsystem can be modified to represent different types of 7-segment displays.

## Support
For any issues or questions regarding the model, please open an issue in the repository
