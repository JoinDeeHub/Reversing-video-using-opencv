# Reversing-video-using-opencv
![cv](https://user-images.githubusercontent.com/81760159/174244077-9866e8be-696a-4369-917a-c5f0aa522da3.jpg)

OpenCV (Open Source Computer Vision Library) is Python library to solve computer vision related problems. OpenCV is a vast library which provides various functions for video operations. Using OpenCV, we can capture a video from the webcam. It lets you create a video capture object which helps to capture videos through webcam and then we can perform desired operations on that video.

To play a video in reverse mode using OpenCV Python

We will get to know the method detecting to play a video in reverse mode using OpenCV Python. 
Here, we are video streaming and playing in reverse mode. Also, we will see a Python program for the same. 


Basic algorithm to capture video using OpenCV Python:-

    Use cv2.VideoCapture() to get a video capture object for the camera.
    Set up an infinite while loop and use the read() method to read the frames using the above created object.
    Use cv2.imshow() method to show the frames in the video.
    Break the loop by clicking specific key on the keyboard.
    
Take a video as input  or can capture using .VideoCapture() function also. 
For playing it in a reverse mode is to first break the video into frame by frame and then simultaneously storing that frames into the list. 
After getting list of frames we perform the iteration over the frames using loop method. 
For playing video in reverse mode, we to iterate over the list of frames in reversal order. Using reverse() method on the list for reversing the order of frames in the list then iterating over the list play the video in reverse order.
