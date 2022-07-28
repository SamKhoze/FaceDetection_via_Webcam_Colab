# FaceDetection_via_Webcam_Colab
This notebook will go through how to access and run code on images and video taken using your webcam.

We used OpenCV's face detection on our Webcam image and video.

# Haar Cascade Classifier
We run a simple object detection algorithm called Haar Cascade on our images and video fetched from our webcam. OpenCV has a pre-trained Haar Cascade face detection model.

# Webcam Images
Running code on images taken from webcam is fairly straight-forward. We will utilize code within Google Colab's Code Snippets that has a variety of useful code functions to perform various tasks.

We will be using the code snippet for Camera Capture to utilize your computer's webcam.

## Webcam Videos
Running code on webcam video is a little more complex than images. We need to start a video stream using our webcam as input. Then we run each frame through our progam (face detection) and create an overlay image that contains bounding box of detection(s). We then overlay the bounding box image back onto the next frame of our video stream.

