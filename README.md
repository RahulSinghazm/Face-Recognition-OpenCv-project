# [Face Recognition OpenCv project](https://github.com/sam2702/Face-Recognition-OpenCv-project)
## Introduction
## [OpenCv](https://en.wikipedia.org/wiki/OpenCV)
![opencv-logo-white](https://user-images.githubusercontent.com/29937202/42703544-832ec5c8-86ea-11e8-91ca-68376e185d23.png)

OpenCV (Open Source Computer Vision) is a popular computer vision library started by Intel in 1999. The cross-platform library sets its focus on real-time image processing and includes patent-free implementations of the latest computer vision algorithms.
### Face Recognition
FacFacial recognition is a biometric software application capable of uniquely identifying or verifying a person by comparing and analyzing patterns based on the person's facial contours. Facial recognition is mostly used for security purposes, though there is increasing interest in other areas of use.ial recognition is a category of biometric software that maps an individual's facial features mathematically and stores the data as a faceprint.
![images](https://user-images.githubusercontent.com/29937202/42703916-9c0c4b8c-86eb-11e8-8a17-282f0e316f1e.jpg)

#### Steps to be followed

-**Prepare training data:** In this step we will read training images for each person/subject along with their labels, detect faces from                               each image and assign each detected face an integer label of the person it belongs to.
-**Train Face Recognizer:** In this step we will train OpenCV's LBPH face recognizer by feeding it the data we prepared in step 1.
-**Testing:** In this step we will pass some test images to face recognizer and see if it predicts them correctly.


## Modules to be Used
-**cv2:** OpenCV module for Python which we will use for face detection and face recognition.
-**os:** We will use this Python module to read our training directories and file names.
-**numpy:** We will use this module to convert Python lists to numpy arrays as OpenCV face recognizers accept numpy arrays.



