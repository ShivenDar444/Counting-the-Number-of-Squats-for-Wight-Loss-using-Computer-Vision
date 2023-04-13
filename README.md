# Counting-the-Number-of-Squats-for-Wight-Loss-using-Computer-Vision

This project is focused on counting the number of squats done by a person using computer vision techniques. It uses OpenCV and Python to detect the person's movements and count the number of squats done. The aim of this project is to provide a tool for people who want to lose weight by doing squats and keep track of their progress.

Requirements
To run this project, you will need the following:

Python 3.x
OpenCV
NumPy
You can install the required packages using the following command:


pip install opencv-python numpy
Usage
To run the project, you can use the squat_counter.py file. The file contains all the code for detecting the person's movements and counting the number of squats done. You can run the file using the following command:


python squat_counter.py
The program will open your webcam and start detecting your movements. To start the counter, stand in front of the camera and press the "s" key. This will start the counter and you can start doing squats. The counter will stop automatically when you finish your squats.

Algorithm
The algorithm used in this project is based on detecting the vertical movement of the person's body. The program first detects the person's body using the Haar Cascade Classifier and then tracks the center of the person's body as they move up and down. The counter is incremented when the person's body moves from a lower position to a higher position, indicating a squat.

Results
The program was tested on a variety of users and was able to accurately count the number of squats done in real-time. The program also provides a visual feedback of the person's movements, highlighting the body parts that are being detected and tracked.

Future Improvements
This project can be further improved by adding features such as:

Tracking the time taken to complete a set of squats
Providing audio feedback to the user after completing a set of squats
Storing the data of the number of squats done over time and visualizing it using graphs
