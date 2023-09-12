
# Face Detection and Recognition System in Smart Homes

In this research, we introduce the design of a face detection and recognition system for smart homes that is capable of recognizing faces using facial recognition technology. This project develops a smart home security system using face recognition through Convolutional Neural Networks (CNN) with an integrated ESP32-CAM camera and CNN model. This system can recognize faces that have been registered in the database.

Prepare several tools to run this system, namely: 

1. ESP32-CAM, 
2. ESP32-Development Board
3. Micro USB cable.


How to run the prototype will be explained below




## Tutorial Prototype

1. Clone this Repository
2. Install "requirements.txt"
2. connect the three hardware devices to a laptop or computer
3. upload "library ESP32-CAM - Arduino.py" to the connected ESP32-CAM in Arduino apps
4. After generating the output IP address, copy the IP address
5. open "sistem.py" and input the IP address into the code
6. install library

import face_recognition

from datetime import datetime

import os

import numpy as np

import urllib.request

import cv2

import pandas as pd

7. run "sistem.py"
