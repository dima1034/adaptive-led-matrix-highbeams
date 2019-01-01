# Adaptive LED Matrix High Beams

## Project Description & Objective

This project was created to demonstrate a more sophisticated approach to modern/standard headlight technology used in present cars on road.
In addition to having the mandatory low and high beams, this project aims to demonstrate how LED technology can be used to create a more
flexible and safe driving experience under low light/dark conditions. The main objective of this technology is to illuminate as much of the 
road as possible while not dazzling other drivers for both oncoming and preceding traffic.
This is made possible in this project with 2 sub-systems in communication. 
First is the module to control the hardware (LED matrix), second is 
a camera to detect vehicles and their locations to determine where to lighten/darken.

#### [**Demo Video**](https://youtu.be/6VwgZgbertE) (Click to see the full video)

![](https://imgur.com/a9QZYnO.gif)

---

## Getting Started

To get this project up and running on your local machine, first, download both LEDController and Python folders. 
* [LEDController](LEDController) folder includes the file for an Arduino microcontroller and is responsible for controlling the LED matrix module based on the input from vehicle detection part (Python).
* [Python](Python) folder includes the Python script vehicleDetect.py for vehicle detection, an inference graph for the pretrained model and a label_map.pbtxt file to map the labels.

Once you're done downloading the folders, the software part of this project would be complete. See Deployment for notes on how to deploy the project in detail.

#### Prerequisites
To successfully run the project, it is required to have the following software and their respective versions:
* Arduino IDE (https://www.arduino.cc/en/main/software)
* Python 3.6 or higher (https://www.python.org/downloads/)
* Tensorflow Object Detection API included in their models repository (https://github.com/tensorflow/models)
* Microsoft Visual Studio (https://visualstudio.microsoft.com/free-developer-offers/)
