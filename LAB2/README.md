Laboratory Activity #2: Working with Analog Signals

## Objectives: 
1. Discuss analog signals and its implementation in a Arduino circuit.
2. Understand analog to digital signal conversion using the map() function.
- The objective of this project is to create a running light effect using multiple LEDs. The LEDs will gradually increase in brightness and then turn off one by one, creating a smooth transition effect.

## Instructions: 
1. Building on the 1st activity. Create the same logic, but applying the following condition:
- Use pins 8 to 12 for the LEDs
- Running light from 12 to 8 with a delay of 1 second (turn all LED on one by one, then turn all LED off one by one)
- use analogWrite() to control the brightness of LEDs
- implement using while() loop and an array to set the pin modes

## Description: 
- This code is designed to control an array of LEDs connected to specific pins on a microcontroller.

## How to Run: 
1. Connect the LEDs to the specified pins on your microcontroller.
2. Upload the code to your microcontroller.
3. The LEDs will gradually increase in brightness and then turn off one by one, creating a running light effect.
