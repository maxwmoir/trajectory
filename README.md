# Trajectory visualiser 
This project takes a webcam stream, detects a target, interpolates its aerial trajectory and graphs its flight path - all in real time.

It uses C++ and OpenCV for image processing, then sends data over a UDP websocket to a python program which uses sympy and Matplotlib to evaluate and graph the results.

## Demo

https://github.com/user-attachments/assets/24a0908e-b284-42f1-8f2c-da9eaa2ecde8

