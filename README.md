# AIR-CANVAS
This is a computer vision based project which tracks a target and uses the said target to draw in air. The motion of the target is captured by a webcam.
A simple and efficient way of teaching using draw in air .

This is a computer vision based project which tracks a target and uses the said
target to draw on air. The motion of the target is captured by a webcam. The video
from the webcam is processed by the computer to get an AR like image overlay on
top of the live footage.This project makes use of a webcam to track the motion of
the target.
The image is masked and the centroid of the target is found. Then a line is drawn
from the current frame to the previous frame.

Packages and Installs required: Python 3.7.6, openCV 3.4.14 ,numpy 1.20.2
