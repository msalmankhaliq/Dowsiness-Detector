# Drowsiness Detection using OpenCV 
This code can detect your eyes and alert when the user is drowsy.


## Applications
This can be used by riders who tend to drive for a longer period of time that may lead to accidents


### Code Requirements
The example code is in Python ([version 3.6](https://www.python.org/download/releases/3.6/) or higher will work). 

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy


### Description

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

### Algorithm

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.

<img src="https://github.com/msalmankhaliq/Dowsiness-Detector/blob/master/eye1.jpg">

### Condition

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.3, Alert is generated.

#### Relationship

<img src="https://github.com/msalmankhaliq/Dowsiness-Detector/blob/master/eye2.png">

#### Summing up

<img src="https://github.com/msalmankhaliq/Dowsiness-Detector/blob/master/eye3.jpg">


For more information, [see](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

### Working Example




### Execution
To see/run the code, open drowsiness_detector.ipynb`

```
drowsiness_detector.ipynb
```
