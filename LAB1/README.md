Laboratory Activity #1: Arduino circuit

Objective:
- The objective of this project is to create a sequential LED lighting system where LEDs turn on and off in a specific order. The system can be modified to control odd or even-numbered LEDs separately.

Description: 
- LED Pins (ledPins[]): An array of pins to which the LEDs are connected.
- Number of LEDs (numLeds): The total number of LEDs in the array.
- Setup: Initializes each LED pin as an output.
- Loop: Controls the sequence in which LEDs turn on and off.

Instructions: 
1. Connect the LEDs: Connect the LEDs to the specified pins on your microcontroller.
2. Upload the Code: Upload the provided code to your microcontroller.
3. Run the Code: The LEDs will turn on and off one by one with a 1-second delay.
4. Modify for Odd/Even LEDs:
5. To control odd-numbered LEDs, change the loop function to turn on and off LEDs at odd indices.
6. To control even-numbered LEDs, change the loop function to turn on and off LEDs at even indices.
