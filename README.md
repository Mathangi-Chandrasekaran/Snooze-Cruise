# Wake the BEEP UP!
Winning the SheHacks + General Motor Challenge <a href="https://devpost.com/software/wake-the-beep-up?_gl=1*1t51oc3*_gcl_au*MTc1NjI3MDEyOC4xNzQzNDU4NzYx*_ga*OTcyODk4NDE5LjE3NDM0NTg3NjE.*_ga_0YHJK3Y10M*MTc0MzQ1ODc2MC4xLjEuMTc0MzQ1ODc2Ni4wLjAuMA">Devpost

Wake the BEEP UP! is a real-time driver drowsiness detection system designed to help prevent accidents caused by driver fatigue. The application uses computer vision to monitor the driver's eyes and detect signs of drowsiness, triggering alerts when the driver appears to be falling asleep.

## Problem
Drowsy Driving is a significant factor in a huge proportion of road accidents globally. 
We wanted to explore how computer vision could be used to detect early signs of driver drowsiness and provide an immediate intervention.

## What it does
We present a simple real-time video monitoring application to alert drivers.
1. The system identifies signs of prolonged eye closure.
2. An audible alert is triggered to wake the driver.
3. The driver is prompted to acknowledge the alert.
4. If the driver does not respond, the system can trigger an automated emergency call through the Twilio API.

## How we built it
We used OpenCV to monitor eyes of the driver and python libraries pygame to send sound alerts to wake up the driver. We used acknowledgement to confirm the driver is up, if not we used twilio to automatically call 911 for emergency


## What's next for Wake The Beep Up
While this is just a way for us to put our step in the game, we have several ideas for the future to enhance our application:
1. Adding visual alerts to pop up/flash the phone screen
2. Adding haptic alerts in the driver seat by integrating hardware devices to create vibrations for alerting
3. Confirming state of being awake through solving a quick math question
4. Adding option to either call a cab in the application
   
## Challenges 
we ran into Integrating the python script to an actual web application was time-consuming

## Accomplishments that we're proud of 
Figuring out a way to automatically call a phone number through python API

## What we learned 
OpenCV for computer vision, CMake tools for development, Python API for calling, Figma for interactive design


## To run the python Code:
Install  & import the following python libraries: opencv-python, dlib, imutils, scipy

And execute the command from python code folder path:
python DrowsinessDetection.py
