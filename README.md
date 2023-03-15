# Face-Recognition using opencv 

This project demonstrates how to perform face recognition using OpenCV and a mobile webcam. It is useful for scenarios where you want to perform face recognition on a remote device such as a robot or a smart home security system.

The project uses OpenCV, which is a popular computer vision library that provides a wide range of tools for image and video processing. OpenCV has a comprehensive set of features for face recognition, including face detection, face tracking, and face recognition algorithms.

The project requires a mobile device with a webcam and a computer running OpenCV. The mobile device can be an Android or iOS device, and the computer can be a Windows or Linux machine. The mobile device and the computer need to be connected to the same Wi-Fi network.

# Installation
To use this project, you will need to install the following dependencies:

Python 3.6 or higher
OpenCV 4.0 or higher
Flask
imutils
numpy

You can install the dependencies using pip:

pip install opencv-python flask imutils numpy


Usage
To use the project, follow these steps:

1. Clone the repository to your computer

2. Open a terminal and navigate to the project directory

3. Run the following command to start the Flask server:

python app.py

4. Open a web browser and navigate to http://<computer-ip>:5000, where <computer-ip> is the IP address of your computer

5. Click the "Start" button to start the webcam on your mobile device

6. Hold your face in front of the mobile device's camera until the green box appears around your face

7. The name of the recognized person will be displayed on the web page

# Credits
This project was inspired by the following articles:

https://www.pyimagesearch.com/2018/09/24/opencv-face-recognition/
https://www.pyimagesearch.com/2015/12/28/increasing-raspberry-pi-fps-with-python-and-opencv/
