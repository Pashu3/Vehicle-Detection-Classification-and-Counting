# Vehicle-Detection Specification and Counting

Vehicle tracking is the process of locating a moving vehicle using a camera. Capturing vehicles in video sequences from surveillance cameras is a demanding application to improve tracking performance. This technology is increasing the number of applications such as traffic control, traffic monitoring, traffic flow, security, etc. The estimated cost of using this technology will be very less. Video and image processing has been used for traffic surveillance, analysis, and monitoring of traffic conditions in many cities and urban areas. Vehicle detection aims to provide information assisting vehicle counting, vehicle speed measurement, identification of traffic accidents, traffic flow prediction, etc. <br>

**MODULES** : <br>
1. Vehicle Detetction
2. Vehicle Classification
3. Vehicle Counting

**FILES**:<br>
- PROGRAMS/<br>
  - [Main.py](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/blob/master/Programs/main.py) : The main program to run the file
  - [Vehicle.py](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/blob/master/Programs/vehicles.py) : Contain the class Vehicle
  - [fgbgMog2.py](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/blob/master/Programs/fgbgMOG2.py) : Simple program to show the backgound subracted video
  - [thresholding.py](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/blob/master/Programs/thresholding.py) : Program to binarize the subracted grayscale video ,basically done after background subtraction
  - [Opening.py](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/blob/master/Programs/Opening.py) : Program to perform morphological opening operation
  - [Closing.py](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/blob/master/Programs/Closing.py) : Program to perform morphological closing operation
- [VIDEOS/ ](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/tree/master/Videos) : Contains the input video for vehicle detection<br>
- [DETECTED VEHICLES/](https://github.com/Pashu3/Vehicle-Detection-Classification-and-Counting/tree/master/detected_vehicles) : Contains the images of vehicles detected from the video
