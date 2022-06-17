# Reversing-video-using-opencv
OpenCV (Open Source Computer Vision Library) is Python library to solve computer vision related problems. OpenCV is a vast library which provides various functions for video operations. Using OpenCV, we can capture a video from the webcam. It lets you create a video capture object which helps to capture videos through webcam and then we can perform desired operations on that video.

To play a video in reverse mode using OpenCV Python

We will get to know the method detecting to play a video in reverse mode using OpenCV Python. 
Here, we are video streaming and playing in reverse mode. Also, we will see a Python program for the same. 


Basic algorithm to capture video using OpenCV Python:-

    Use cv2.VideoCapture() to get a video capture object for the camera.
    Set up an infinite while loop and use the read() method to read the frames using the above created object.
    Use cv2.imshow() method to show the frames in the video.
    Break the loop by clicking specific key on the keyboard.
