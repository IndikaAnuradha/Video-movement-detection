# Video Movement Detection – Running Detection Using OpenCV

This project detects fast movement (e.g., running) in videos using OpenCV by analyzing frame-by-frame motion and highlighting fast-moving objects with bounding boxes.

## 📹 What It Does

- Reads a video file.
- Applies frame differencing and contour detection.
- Computes speed of moving objects based on centroid movement.
- Draws a red rectangle around objects that are moving fast (running).

## 🛠️ Requirements

Make sure you have Python 3 installed. Then install the required libraries:

```bash
pip install opencv-python numpy
