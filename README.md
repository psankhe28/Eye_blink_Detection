#Eye blink detection👀

Detecting blink of eyes using haar cascade.

###Table of Contents

-[Description]{#description}
-[Implementation]{#implementation}
-[Technologies]{#technologies}
-[How to Use]{#how-to-use}

##Description📝

Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001. It is a machine learning-based approach where a cascade function is trained from a lot of positive and negative image.Using this cascade,
I have created a eye blink detector.

##Implementation📝
-The algorithm first detects the face using the haar cascade.
-Using this face as input,the eye detection cascade detects the eyes.
-If eyes are open,after pressing "s" the detector starts its process to detect blinking of eyes.
-If the eyes are blink,it prints "Blink detected" in the console.

##Technologies💻

-Python 3.9
-Libraries used-OpenCv,Numpy
-Haar Cascade for face and eyes

##How to Use📃
Make sure following libraries are installed before execution
1. openCV
```
pip install opencv-python
```
2. numpy
```
pip install numpy
```
