# face-detection_openCV
 In this tutorial you will learn how to perform OpenCV Face Recognition to accurately recognize faces in images and video streams.


Sublime text 3 Guide for implementing Face Recognition and Face Verification algorithms with OpenCV framework.

- Face Recognition library used for detecting landmarks on faces.
- Code involves implementation of triple loss function, togather with implementation of face verification and face recognition algorithms.
- Inspired from deeplearning.ai Specialization Assignment and used pre-trained models and some of the utility functions from the course
- Encoded images to 128 dimensional embedding vectors.

function which i have used for recognizer OpenCV : CascadeClassifier 

face_cascade = cv2.CascadeClassifier('cascades/data/haarcascade_frontalface_alt2.xml')
eye_cascade = cv2.CascadeClassifier('cascades/data/haarcascade_eye.xml')
smile_cascade = cv2.CascadeClassifier('cascades/data/haarcascade_smile.xml')


requirements : numpy==1.14.2 opencv-contrib-python==3.4.0.12
runtime : python-3.7.4
