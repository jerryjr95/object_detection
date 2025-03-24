# object_detection
This object detection system is a real-time web-based application using Flask, OpenCV, and YOLOv5 to detect and track objects in a video feed. The system estimates the distance of detected objects using a known width and focal length calculation method. If an object is detected within a predefined alert distance (0.75m), an audio beep is triggered using sounddevice to alert the user.

Key Features:
Real-Time Object Detection: Uses the YOLOv5 deep learning model to detect objects with high accuracy.

Distance Estimation: Calculates the distance of detected objects based on their pixel width in the image.

Audio Alert System: Plays a warning beep when an object is too close to the camera.

Web-Based Interface: Provides a live video feed through a Flask web application.

Efficient Processing: Uses OpenCV for video handling and visualization.

This system is particularly useful for collision warning systems, security applications, and smart assistance tools where proximity-based alerts are needed.
