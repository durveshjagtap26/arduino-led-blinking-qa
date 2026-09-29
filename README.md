# Arduino LED Blinking with QA Tracking

## Project Description
This project demonstrates a basic embedded system using an Arduino board to blink an on-board LED. The code configures digital pin 13 as an output and uses a continuous loop to toggle the power state of the LED.

## How It Works
* **Setup Phase:** Digital Pin 13 is initialized as an `OUTPUT` pin.
* **Execution Loop:** 
  1. Pin 13 is set to `HIGH` (Turns the LED ON).
  2. The system pauses for 1000 milliseconds (1 second).
  3. Pin 13 is set to `LOW` (Turns the LED OFF).
  4. The system pauses for another 1000 milliseconds (1 second).
  * This cycle repeats indefinitely.

## Technical Specifications
* **Hardware:** Arduino Uno (or compatible board), Built-in LED on Pin 13.
* **Software Environment:** Arduino IDE, Embedded C++.

