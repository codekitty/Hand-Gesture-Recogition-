# Hand-Gesture-Recogition-
Recognize hand gestures from video - Class Project, MatLab based

To run the script type "interpret_gesture" in your matlab command window. 
A file chooser will pop up and you can select a video file (try one of the example files I've added to this project)

interpret_gesture.m 
accepts video (filename) of a hand on a dark background.
The output is a series of tuples describing the hand gestures:
left (1 0)
right (-1 0)
up (0 1)
down (0 -1)
diagonally (1 1), (-1 1), (-1 -1), or (1 -1). 
The script also outputs of vector of 0,1,and 2's, describing the hand type was displayed in during the sweeping motion
fist (0)
splayed (1)
peace sign (2)

The script identifies hands by selecting for continous bright regions on the image and counting convext defects.

Here is a video of of the script in action:
https://www.youtube.com/watch?v=lMOfdBqoBj0
