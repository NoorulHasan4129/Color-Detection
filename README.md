
# Color Detection using OpenCV and Python
This project demonstrates color detection in real-time using OpenCV and Python. It includes two main scripts: main.py for live color detection from a webcam and util.py containing utility functions for defining color ranges in HSV format.

# Features
<br>
Detects multiple colors (blue, yellow, green) using predefined HSV ranges.
<br>
Provides real-time feedback with bounding boxes and labels around detected colors.
<br>
Adjusts brightness dynamically to enhance color detection accuracy.
# How It Works
<br>
# Color Detection Script (main.py):
<br>
Utilizes webcam feed (cv2.VideoCapture(0)) to capture frames.
<br>
Converts frames to HSV format for better color detection.
<br>
Applies predefined HSV ranges from util.py to detect colors.
<br>
Draws bounding boxes and labels around detected colors in the live feed.
<br>
Includes instructions to close the application using the ESC key.

# Utility Functions (util.py):
<br>
Defines HSV ranges for colors like blue, yellow, and green.
<br>
Provides flexibility to add or modify color ranges for different applications.
<br>
Handles unsupported color warnings gracefully.
