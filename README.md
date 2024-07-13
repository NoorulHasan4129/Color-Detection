
#Color Detection using OpenCV and Python
This project demonstrates color detection in real-time using OpenCV and Python. It includes two main scripts: main.py for live color detection from a webcam and util.py containing utility functions for defining color ranges in HSV format.

#Features
Detects multiple colors (blue, yellow, green) using predefined HSV ranges.
Provides real-time feedback with bounding boxes and labels around detected colors.
Adjusts brightness dynamically to enhance color detection accuracy.
#How It Works
#Color Detection Script (main.py):
Utilizes webcam feed (cv2.VideoCapture(0)) to capture frames.
Converts frames to HSV format for better color detection.
Applies predefined HSV ranges from util.py to detect colors.
Draws bounding boxes and labels around detected colors in the live feed.
Includes instructions to close the application using the ESC key.
#Utility Functions (util.py):

Defines HSV ranges for colors like blue, yellow, and green.
Provides flexibility to add or modify color ranges for different applications.
Handles unsupported color warnings gracefully.
