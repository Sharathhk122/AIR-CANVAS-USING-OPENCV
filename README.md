

```markdown
# Air-Canvas-with-ML
A Computer Vision project implemented with OpenCV and Machine Learning using Mediapipe.

## Project Overview
Ever wanted to draw your imagination by just waiving your finger in the air? In this project, we build an **Air Canvas** that can draw anything on the screen based solely on the motion of your hands, detecting the landmarks on your hand. It’s a great project for showcasing machine learning skills and can be added to a resume to demonstrate computer vision techniques.

This project utilizes **Hand Landmarks Detection** and **Tracking** to detect finger movements in real-time. It is implemented using Python, OpenCV, and Mediapipe.

## Algorithm

1. **Frame Capture**: Start reading the video frames and convert the captured frames to HSV color space for better color detection.
2. **Canvas Setup**: Prepare the canvas and display the ink buttons for drawing.
3. **Hand Detection**: Adjust Mediapipe's initialization to detect only one hand.
4. **Landmark Detection**: Use the Mediapipe hand detector to pass the RGB frames and detect the hand landmarks.
5. **Tracking Landmarks**: Detect the landmarks, find the coordinates of the forefinger, and store them in an array for drawing points on the canvas.
6. **Drawing**: Draw the stored points on the canvas and update the frame.

## Features

- **Real-time Drawing**: Draw freely on the screen by moving your finger in the air.
- **Hand Gesture Recognition**: Tracks the position of your fingers using hand landmarks.
- **Canvas with Ink Buttons**: Interactive canvas with predefined ink options to draw various styles.
- **Python & OpenCV**: Built using Python’s OpenCV library, widely used for computer vision tasks.
- **Mediapipe Integration**: Uses Google’s Mediapipe library for detecting hand landmarks with ease.
- **Single-Hand Detection**: Optimized for detecting one hand at a time.
- **Intuitive Controls**: Simple to use, requiring no physical controllers, just your hand movement.

## Requirements

Before setting up the project, make sure you have Python 3 installed. Additionally, you will need to install the following Python libraries:

- **NumPy**: For numerical operations.
- **OpenCV**: For computer vision tasks like image manipulation.
- **Mediapipe**: For hand gesture recognition.

### Installation Steps

1. **Install Python 3**:
   If you don’t have Python 3 installed, download it from the official Python website:
   
   [Download Python 3](https://www.python.org/downloads/)
   
   After installation, verify Python is correctly installed by running the following command in your terminal:
   ```bash
   python --version
   ```

2. **Install Required Libraries**:
   Open a terminal or command prompt and install the necessary libraries using `pip`:
   ```bash
   pip install numpy opencv-python mediapipe
   ```

3. **Verify Installation**:
   After installation, verify that the libraries are installed correctly by running a Python script or entering the Python interpreter.

4. **Run the Air Canvas Project**:
   Once the setup is complete, run the `air_canvas.py` script to start drawing with your hands.
   ```bash
   python air_canvas.py
   ```

## Screenshots

Below are some screenshots showcasing the project in action:

![Air Canvas - Screenshot 1](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%202024-11-08%20200936.png)
![Air Canvas - Screenshot 2](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(892).png)
![Air Canvas - Screenshot 3](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(893).png)
![Air Canvas - Screenshot 4](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(894).png)
![Air Canvas - Screenshot 5](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(891).png)

---

