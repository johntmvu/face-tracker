```markdown
# Real-Time Face Recognition Demo

This repository contains a real-time face recognition demo using Python, OpenCV, and the `face_recognition` library. It captures video from your webcam, detects faces, and identifies them if they match known faces in the dataset.

## Features

- **Real-Time Face Detection**: Uses OpenCV to capture live video from your webcam.
- **Face Recognition**: Matches faces against a set of known images using the `face_recognition` library.
- **Optimized Performance**: Processes video frames at a reduced resolution and every other frame to improve speed.

## Installation

1. **Clone the repository**:
    ```bash
    git clone <your-repository-url>
    cd <repository-directory>
    ```

2. **Install dependencies**:
    Make sure Python is installed, then install the required libraries with:
    ```bash
    pip install face_recognition opencv-python numpy
    ```

3. **Add Known Faces**:
    - Save images of the people you want to recognize in the same directory as the script, naming them descriptively (e.g., `obama.jpg`, `biden.jpg`).
    - Update the file to load these images for recognition.

## Usage

Run the following command to start the demo:

```bash
python face_recognition_demo.py
```

### Key Bindings

- **Press 'q'** to exit the program.

## How It Works

1. **Face Encoding**: Preloads and encodes faces from known images.
2. **Frame Processing**: Captures video from the webcam, downsizes frames for faster processing, and converts color format.
3. **Face Matching**: Compares detected faces with known encodings and displays a name if a match is found.

## Credits

This script is based on a demo from the [`face_recognition`](https://github.com/ageitgey/face_recognition) library by Adam Geitgey. It has been adapted and optimized for real-time use.

## Requirements

- Python 3.7+
- OpenCV (`opencv-python`)
- `face_recognition` library (requires `dlib`)

## License

MIT License
```

This README gives an overview of the project, installation steps, usage instructions, and credits, covering the essential information for users and contributors.
