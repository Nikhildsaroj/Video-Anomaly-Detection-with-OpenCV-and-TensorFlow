# Video Anomaly Detection with OpenCV and TensorFlow

### Overview
This project showcases the implementation of video anomaly detection using OpenCV and TensorFlow. Video anomaly detection involves identifying unusual or unexpected events or objects in a video stream. In this project, the focus is on detecting anomalies, specifically the presence of sharks, in a video stream using object detection techniques with a pre-trained TensorFlow model (Faster R-CNN Inception v2).

### Features
- **Object Detection**: Utilizes a pre-trained TensorFlow model for object detection on each frame of the video stream, marking anomalies where sharks are detected.
- **Background Subtraction**: Implements background subtraction using the Gaussian Mixture-based Background/Foreground Segmentation method (MOG2) from OpenCV to highlight moving objects.
- **Interactive Restricted Area Selection**: Allows users to interactively select a restricted area in the video stream by defining four points using mouse clicks.
- **Anomaly Detection using Optical Flow**: Detects anomalies using optical flow between consecutive frames by computing anomaly scores for player movements.
- **Threshold Setting and Alert Triggering**: Defines thresholds for anomaly scores to determine when anomalies should be triggered, facilitating timely responses to unusual events or objects.

### Demo
- **Python Script**: [Video Anomaly Detection Project](https://github.com/Nikhildsaroj/Video-Anomaly-Detection-with-OpenCV-and-TensorFlow/blob/main/Video_Anomaly_Detection_project(Nikhil_Saroj)%20(3).ipynb)
- **Demo Video**: [Shark Detection Demo Video](https://github.com/Nikhildsaroj/Video-Anomaly-Detection-with-OpenCV-and-TensorFlow/blob/main/sharkdetection.avi)

### Conclusion
This project offers valuable insights into video processing and anomaly detection algorithms, particularly in the context of object detection and identification of unusual events in video streams. It equips users with practical skills and knowledge applicable in various real-world scenarios, including drone technology and surveillance systems.

