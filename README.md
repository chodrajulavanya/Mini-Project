# Drowsiness Detection System

This Python script implements a drowsiness detection system using facial landmarks and computer vision techniques. The system monitors the eyes and mouth of a person through a webcam feed and alerts if signs of drowsiness or yawning are detected.

## Requirements

- Python 3.x
- OpenCV
- imutils
- dlib
- scipy
- numpy

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/drowsiness-detection.git
    ```

2. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Download the pre-trained shape predictor model:**

    Download the shape predictor model from [here](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and place it in the project directory.

## Usage

Run the script `drowsiness_detection.py` with the following command:

```bash
python drowsiness_detection.py
