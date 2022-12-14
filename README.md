# Volume-Control-Using-Gesture

This Repository Consists of two files:-
  - HandTrackingModule.py
  - VolumeHandControl.py

# HandTrackingModule
  - Uses OpenCV and MediaPipe to detect and track the hand using the "Hand Landmark Model".
  - OpenCV is a library used for computer vision applications. With help of OpenCV, we can build an enormous number of applications that work better in real-time. Mainly it is used for image and video processing.
  - MediaPipe is a framework mainly used for building audio, video, or any time series data. With the help of the MediaPipe framework, we can build very impressive pipelines for different media processing functions.
  - Hand Landmark Model 
      ![image](https://user-images.githubusercontent.com/81406458/207238073-78ccbd60-fed7-496d-891f-443dbf94a17a.png)

# VolumeHandControl
  - Uses the HandTrackingModule.py mentioned earlier to detect hands and track the movemnet of the hand using the above mentioned Hand Landmark Model.
  - Uses pycaw 
  - pycaw is a python Core Audio Windows Library 
  - Link to [pycaw](https://github.com/AndreMiras/pycaw) github Repository
 
# Demostration Video

https://user-images.githubusercontent.com/81406458/207616104-eced6bc1-0d72-4167-a0c2-761182b86755.mp4


