# RGB-Color-Detection-Using-Open-CV---Project
# Overview:
For a robot to visualize the environment, along with the object detection, detection of its color in real-time is also very important.

Why this is important? : Some Real-world Applications
In self-driving car, to detect the traffic signals.
Multiple colour detection is used in some industrial robots, to performing pick-and-place task in separating different colored objects.
This is an implementation of detecting multiple colors (here, only red, green, blue colors have been considered) in real-time using Python programming language.

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





