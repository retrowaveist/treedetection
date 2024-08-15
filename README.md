# treedetection
Using HoG to detect tree cover in satellite imgs
# Implementation of HoG algorithm to extract a tree from a remotely sensed image

## Introduction
This project focuses on the identification of tree locations in remotely sensed images through the implementation of the Histogram of Oriented Gradients (HoG) algorithm. The HoG technique extracts features from the images that are then used to detect and identify trees effectively.

## Project Members
Mariyam Saqib - 210040090
Sabita Krishna - 210110068
Shraddha Kamath - 210040148
Shubhang Shangvi - 21D180039


## Instructor
Prof. B.K Mohan

## Prerequisites
- Required software: Python 3.8, PyInstaller
- Libraries: NumPy, OpenCV, tkinter, skimage
- Any standard operating system (Windows, macOS, Linux)

## Installation
To set up the project environment, ensure Python 3.x is installed along with the necessary libraries:
pip install numpy opencv-python

## Running the Application
How to run the executable:
1. Navigate to the `dist` folder.
2. Double-click on `gnr_group21.exe` 

## How to Use
Launching the GUI:
Open the executable to start the graphical user interface.
Using the GUI:
Use the file selection dialog to choose a remotely sensed image.
This runs the HoG and subsequent tree detection algorithms
The GUI will display the processed images of the tree detection results.
## Input and Output
- **Input**: High-resolution aerial or satellite images.`images.jpg`
- **Parameters**: The image is first converted to grayscale and resized to 128x64 pixels for uniformity.
HoG descriptors are calculated and visualized.
- **Output**: The output includes images showing tree locations with detected features

## Troubleshooting
- Issue: Application does not start.
  - Solution: Ensure all prerequisites are installed and that the executable is in the correct directory as specified.
- GUI Issue: File dialog does not open.
  - Solution: Check for permission issues or reinstall the application.

References
Histogram of Oriented Gradients - Towards Data Science
HOG Video Tutorial - YouTube
Histogram of Oriented Gradients - Wikipedia
Roboflow Public Datasets

