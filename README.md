**Face recognition**

This repository contains the relevant code for face detection via the pretrained Haar features based cascade classifier provided by OpenCV.

`face_recog.ipynb` contains the Python code for a live video, e.g. a webcam:

![face-detec livecam](https://github.com/d-kleine/face_recognition_webcam/blob/main/face_recog_webcam.gif)


`face_recog_video.ipynb` contains the Python code for a video file. It writes a new mp4 video file that is using the original video frames and drawing a square indicating a detected face by the above mentioned cascade classifier:

![face-detec videofile_orig](https://github.com/d-kleine/face_recognition_webcam/blob/main/face_recog_video1.gif)

![face-detec videofile_final](https://github.com/d-kleine/face_recognition_webcam/blob/main/face_recog_video2.gif) 
