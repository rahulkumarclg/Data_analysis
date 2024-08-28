# Snapchat-Like Filter with OpenCV and cvzone

This project demonstrates a simple Snapchat-like filter application using Python, OpenCV, and cvzone. The script captures real-time video from your webcam, detects faces, and overlays an image (e.g., glasses) onto the detected faces.

## Features

- **Real-Time Face Detection:** The script uses Haar Cascade classifier to detect faces in the webcam feed.
- **Image Overlay:** It overlays a predefined image (like glasses) onto the detected faces.
- **Live Display:** The output is displayed in real-time, showing the applied filter on your face.
- **Exit Mechanism:** Press the 'q' key to exit the application.

## Installation

### Prerequisites

- Python 3.x
- OpenCV
- cvzone

### Installing Required Libraries

You can install the necessary Python libraries using pip:

```bash
pip install opencv-python cvzone
```
## Acknowledgments

- The `cvzone` library is a great utility for computer vision tasks.
- The Haar Cascade XML files are provided by OpenCV.
