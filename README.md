# adaptive-vehicle-headlamps
A mini project demonstrating automatic adaptive headlamp control in vehicles.

# The Objective
The automotive industry is growing at an accelerating pace, thanks to an ever-increasing global requirement for vehicular mobility. This alone has led to a significant increase in automobile activity across the board and around the clock, without taking into consideration other positive economic factors; an increase in vehicular activity includes an increase in vehicular activity during dimly-lit and night-time conditions.

The aim of this project is to solve two of the most persistent issues with regards to vehicle headlamps and their handling, by automating their utilization with a specific embedded control solution that can be calibrated and customized as and when required.

# The Theory
## Components
1x Arduino Uno
1x Light Dependent Resistor
1x Light Emitting Diode
1x 220 Ω Limiting Resistor
1x External Power Supply (of any kind, stepped down to 5V DC

## Implementation
The hardware components are connected as follows:
The LDR is connected to an analog pin that is set to INPUT mode, and is grounded.
The LED is connected to a digital pin with PWM capability that is set to OUTPUT mode. The LED is grounded separately through a 220 Ω limiting resistor.
The controller board is powered up using a 5-volt external supply - this is either done directly, or through a buck-boost converter in order to step up or step down any external DC voltage provided to the board.

The software part of this project can be implemented using the Arduino IDE, which can be found here.

# The Project
![image](https://user-images.githubusercontent.com/102752322/167880621-c6398e16-3232-4135-890b-379667afa8ea.png)
