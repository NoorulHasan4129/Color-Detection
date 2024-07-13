
# Color Detection using OpenCV and Python
This project demonstrates color detection in real-time using OpenCV and Python. It includes two main scripts: main.py for live color detection from a webcam and util.py containing utility functions for defining color ranges in HSV format.

# Features
<ul>
<li>Detects multiple colors (blue, yellow, green) using predefined HSV ranges.</li>
<li>Provides real-time feedback with bounding boxes and labels around detected colors.</li>
<li>Adjusts brightness dynamically to enhance color detection accuracy.</li>
</ul>

# How It Works

# Color Detection Script (main.py):
<ul>
<li>Utilizes webcam feed (cv2.VideoCapture(0)) to capture frames.</li>
<li>Converts frames to HSV format for better color detection.</li>
<li>Applies predefined HSV ranges from util.py to detect colors.</li>
<li>Draws bounding boxes and labels around detected colors in the live feed.</li>
<li>Includes instructions to close the application using the ESC key.</li>
</ul>

# Utility Functions (util.py):
<ul>
<li>Defines HSV ranges for colors like blue, yellow, and green.</li>
<li>Provides flexibility to add or modify color ranges for different applications.</li>
<li>Handles unsupported color warnings gracefully.</li>
</ul>
