# Real-Time Face Recognition Demo

This repository contains a real-time face recognition demo using Python, OpenCV, and the `face_recognition` library. It captures video from your webcam, detects faces, and identifies them if they match known faces in the dataset.

## Features

- **Real-Time Face Detection**: Uses OpenCV to capture live video from your webcam.
- **Face Recognition**: Matches faces against a set of known images using the `face_recognition` library.
- **Optimized Performance**: Processes video frames at a reduced resolution and every other frame to improve speed.

## Installation

1. **Clone the repository**:
    ```
    git clone https://github.com/johntmvu/face-tracker.git
    cd face-tracker
    ```

2. **Install dependencies**:
    Make sure Python is installed, then install the required libraries with:
    ```
    pip install face_recognition opencv-python numpy
    ```

3. **Add Known Faces**:
    - Save images of the people you want to recognize in the same directory as the script, naming them descriptively (e.g., `obama.jpg`, `biden.jpg`).
    - Update the file to load these images for recognition.

## Usage

Run the following command to start the demo:

```
python face_recognition_demo.py
```

## Key Bindings

    - Press 'q' to exit the program.

## Credits

    This script is based on a demo from the face_recognition library by Adam Geitgey. It has been adapted and optimized for real-time use.