# RGB-Color-Detection-Using-Open-CV---Project
# Overview:
* The RGB Color Detection using OpenCV project is designed to allow a robot to visualize its environment by detecting the colors of objects in real-time.
* Along with object detection, identifying the color of the objects is crucial for various real-world applications, especially in robotics and autonomous systems.

# Why is this important?
* Color detection plays a significant role in several practical applications, such as:

* Self-driving cars: Detecting traffic signals by their color (e.g., red, green, yellow).
* Industrial robots: Performing pick-and-place tasks by distinguishing between objects of different colors, enabling the robot to sort or manipulate items based on color.
* In this project, multiple colors—specifically red, green, and blue—are detected in real-time using Python and OpenCV, providing a practical solution for environments where color-based object identification is needed.

# Python Libraries Used:

1) Numpy
2) OpenCV-Python

# Work Flow Description:

Step 1: Input: Capture video through webcam.

Step 2: Read the video stream in image frames.

Step 3: Convert the image Frame in BGR(RGB color space represented as three matrices of red, green and blue with integer values from 0 to 255) to HSV(hue-saturation-value) color space.

Hue - describes the amount of colour (0-179) range

Saturation – describes the amount of gray colour in that colour and

Value - describes the brightness or intensity of the colour. This can be represented as three matrices in the range of 0-179, 0-255 and 0-255 respectively.

Step 4: Define the range of each colour and create the corresponding mask.

Step 5: Defining mask for RGB colours

Step 6: bitwise_and operator between the image frame and mask is performed to specifically detect that particular colour and discard others.

Step 7: Output: Detection of the colours in real-time.





