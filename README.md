# Hand Gesture recognition
This project enables you to perform various functions on videos/basic games (Or anything that requires the arrow keys and spacebar) using 2 HC-SR04 sensors and an Arduino.

## Instructions to get it to work

### Arduino
Upload the code in the `gestureRecognition.ino` file on to your arduino microcontroller.
Make sure you connect your microcontroller to the correct trigger and echo pins as written in the code.

### Python
You  will need a few python libraries for this to work i.e. `pyserial` and `pyautogui`.

To install the respective libraries, use a terminal to navigate to the directory where Python has been installed and use these commands
```
python -m pip install pyserial
python –m pip install pyautogui
```
Change the port number and the baud rate to the required values in the `conn.py` code (line 5).

Run the code

## Actions

- Use 2 hands at approximately a foot away to play/puase the video (spacebar). 
- Start from near the right sensor and move away to fast forward (left arrow key).
- Start away from the right sensor and move in to Rewind (right arrow key). 
- Start from near the left sensor and move away to increase volume (Up arrow key).
- Start away from the left sensor and move in to decrease volume (Down arrow key). 
- You can use this with anything that may require the spacebar and arrowkeys and not just control videos