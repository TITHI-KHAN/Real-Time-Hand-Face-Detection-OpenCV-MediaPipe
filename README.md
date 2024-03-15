# Real-Time-Hand-Face-Detection-OpenCV-MediaPipe

## To run the code, please either use "Visual Studio" or "Jupyter Notebook from Anaconda Navigator".

### For the project video, please check the "Project Video" file. Thank you.

![2_1](https://github.com/TITHI-KHAN/Real-Time-Hand-Face-Detection-OpenCV-MediaPipe/assets/65033964/5b7b12fe-26a1-4c3c-8e8d-e6cf10e944b1)

![2_2](https://github.com/TITHI-KHAN/Real-Time-Hand-Face-Detection-OpenCV-MediaPipe/assets/65033964/da89a41c-9393-4eac-a6d6-ae9e9a3c64a1)

![2_3](https://github.com/TITHI-KHAN/Real-Time-Hand-Face-Detection-OpenCV-MediaPipe/assets/65033964/c701e36b-bde5-47eb-aadc-320809e2d440)

![2_4](https://github.com/TITHI-KHAN/Real-Time-Hand-Face-Detection-OpenCV-MediaPipe/assets/65033964/835aeeb1-bb5b-4c03-b953-f6c051d8a99f)

![2_5](https://github.com/TITHI-KHAN/Real-Time-Hand-Face-Detection-OpenCV-MediaPipe/assets/65033964/27b61b0b-2383-4ca0-866d-e57a999240da)

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
