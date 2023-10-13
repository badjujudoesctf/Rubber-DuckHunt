# Rubber DuckHunt

Rubber DuckHunt is a program that captures key presses and keeps track of certain statistics about the captured key presses, such as the time between presses and the keys that have been pressed. It also has logic for detecting abnormal keystroke patterns, such as an unusual keystroke speed, and can output this information to the console or the Windows event log..

## Building

This program can be built on Windows with Visual Studio, using the following steps:
1. Open the project in Visual Studio.
2. Build the project in Release mode.
3. Run the program 

## Features
- Track key presses and statistics about the captured key presses, such as the time between presses and the keys that have been pressed.
- Detect unusual keystroke speed.
- Detect when a new keyboard device is plugged in
- Output information to the console and Windows event log.

## Usage

The program can be used to monitor for keystroke injection attacks.
It should detect every keystroke from any keyboard, the typing speed and if new devices as been plugged. 

If verbose is active (default), The output will show you the Detection Flags status.  
If something suspicious is detected, you can find the log in the Windows Application Events with ID 1337.

When in DEBUG mode,   ESC key to close the program

## Note

It's important to keep in mind that the use of keyloggers is generally illegal and unethical, unless it is done with the informed consent of the people being monitored. Additionally, it is a best practice to keep this kind of software on a secure network, and the use should be compliant with the laws and regulations of the countries or states where the software will be used.

Plus... it appear that this keylogging technique is not flag by popular EDR vendors.

![image](https://github.com/t3kn1cs/Rubber-DuckHunt/assets/7936289/e8cb6760-ad3e-468d-a7ba-f2cbeb185e21)

