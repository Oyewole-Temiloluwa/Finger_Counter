# Finger Counting Project

## Overview
The Finger Counting Project uses computer vision techniques to detect and count the number of fingers shown to the camera. This project is useful for developing hand gesture-based interfaces and enhancing interaction with various applications.

## Features
- Real-time hand tracking
- Finger detection and counting
- Visual feedback through a webcam feed

## Requirements
- Python 3.x
- OpenCV
- Mediapipe

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/FingerCountingProject.git
    ```
2. Navigate to the project directory:
    ```bash
    cd FingerCountingProject
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Files

### FingerCountingProject.py
This is the main script that runs the finger counting application. It captures video from the webcam, processes the frames to detect the hand, and counts the number of fingers displayed.

### HandTrackingModule.py
This module contains the hand tracking functionalities. It leverages Mediapipe to detect hand landmarks and provides utilities to find the position of fingers and count them.

## Usage
1. Ensure you have a webcam connected to your computer.
2. Run the main script:
    ```bash
    python FingerCountingProject.py
    ```
3. A window will open showing the webcam feed with hand tracking and finger counting functionalities.

## How It Works
1. The `HandTrackingModule.py` uses Mediapipe to detect hand landmarks in real-time.
2. The `FingerCountingProject.py` captures video frames from the webcam, processes these frames to identify hand landmarks, and then determines which fingers are up.
3. The number of fingers detected is displayed on the screen.

## Contributing
Feel free to fork this repository, make your changes, and submit a pull request. Contributions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The Mediapipe framework by Google for hand tracking.
- OpenCV for providing the computer vision functionalities.
