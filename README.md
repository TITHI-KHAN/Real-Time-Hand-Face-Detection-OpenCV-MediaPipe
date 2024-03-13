# Real-Time-Hand-Face-Detection-OpenCV-MediaPipe

### Utilizes only the MediaPipe library for hand gesture detection.

### Relies solely on hand landmarks detected by the MediaPipe Hands module for gesture recognition.

The provided Python script utilizes the MediaPipe library to detect hand gestures and facial landmarks simultaneously in real-time video captured from a webcam using OpenCV.

Here's a brief overview of the script:

1. It imports the necessary libraries: `cv2` for OpenCV, `mediapipe` for hand and face detection, and `time`.

2. The script initializes webcam capture using `cv2.VideoCapture()`.

3. Within the main loop, it processes each frame from the webcam feed:

   a. Hand landmarks are detected and drawn on the frame using the MediaPipe hands module.
   
   b. Face landmarks are detected and drawn on the frame using the MediaPipe face mesh module.

4. The processed frame, containing both hand gestures and facial landmarks, is displayed in a window named 'Hand Gesture and Face Detection'.

5. The loop continues until the user exits by pressing the 'q' key.

6. Finally, it releases the webcam and closes all OpenCV windows.

The script provides a comprehensive demonstration of real-time hand gesture and face landmark detection, making it suitable for applications such as gesture-based interfaces, emotion recognition, and facial expression analysis.
