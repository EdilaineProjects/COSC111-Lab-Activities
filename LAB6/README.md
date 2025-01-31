Laboratory Activity#6: 

Objective: 
- The objective of this project is to create a system that detects button presses using an Arduino and sends the button state to a Python script, which then calls an API based on the button state.
- Building connection to another device using Wi-Fi or Hotspot connection. The group created a code for button in Arduino, and the other device that is connected in Wi-Fi or Hotspot connection has the LED in Breadboard and code in Arduino.

Description: 
In Arduino Code:
- Button Pin (buttonPin): Connects the button to pin 12.
- Button State (buttonState): Reads the state of the button (pressed or not pressed).
- Serial Communication: Initializes serial communication to send the button state to the Python script.

In Python Code:
- Serial Connection: Establishes a serial connection with the Arduino.
- API Endpoint (api_url): The URL of the API to be called based on the button state.
- Button State Handling: Reads the button state from the Arduino and calls the API to turn the LED on or off based on the button state.

How to Run: 
1. Connect the button to the specified pin on your Arduino.
2. Upload the Arduino code to your Arduino board.
3. Run the Python script on your computer.
4. Press the button to send the button state to the Python script, which will call the API to control the LED.
