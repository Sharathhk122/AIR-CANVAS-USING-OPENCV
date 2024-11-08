# Air-Canvas-with-ML
Computer vision project implemented with OpenCV with Machine learning using the Mediapipe

Ever wanted to draw your imagination by just waiving your finger in air. In this post we will learn to build an Air Canvas which can draw anything on it by just motion of our hands and noticing the landmark on the hand . A very beautiful project for resume of machine learning people.
We will be using the computer vision techniques of OpenCV to build this project. The preffered language is python due to its exhaustive libraries and easy to use syntax but understanding the basics it can be implemented in any OpenCV supported language.

Here Hand landmarks detection and tracking is used in order to achieve the objective. 


# Algorithm

1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3. Adjust the values of teh mediapipe intilization to detect one hand only.
4. Detect teh landmarks by passing the RGB frame to the mediapipe hand detector
5. Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
6. Finally draw the points stored in array on the frames and canvas .

Requirements: python3 , numpy , opencv, mediapipe installed on your system.

Installation

To set up the Air Canvas project, you'll need to install the required dependencies: Python 3, NumPy, OpenCV, and MediaPipe. Here’s how you can install them:

1. Install Python 3:

If you haven't already, install Python 3 from the official website:

[Download Python 3](https://www.python.org/downloads/)

After installing, verify the installation by running:

python --version

2. Install Required Libraries:

Open a terminal or command prompt and install the necessary libraries using pip:


pip install numpy opencv-python mediapipe

numpy: For numerical operations.

opencv-python: For computer vision tasks.

mediapipe: For hand gesture recognition.

3. Verify Installation:

After installation, verify that the libraries are installed correctly by running a Python script or entering the Python interpreter.

Screenshots

![ss1](https://user-images.githubusercontent.com/88366253/147323134-08a4b394-a4c1-4fad-b955-93cadeb681fb.png)

![ss1](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(892).png)

![ss1](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(893).png)

![ss1](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(894).png)

![ss1](https://github.com/Sharathhk122/AIR-CANVAS-USING-OPENCV/blob/main/Screenshot%20(891).png)



