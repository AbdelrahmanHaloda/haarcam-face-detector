# HaarCam Face Detector

A small real-time face detection project using Python, OpenCV, and a Haar Cascade classifier.

The project opens the webcam, reads video frames, converts each frame to grayscale, detects faces using a pre-trained Haar Cascade XML model, and draws rectangles around detected faces.

---

## Project Structure

```text
haarcam-face-detector/
├── camera.py
├── haarcascade_frontalface_default.xml
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Tools Used

* Python
* OpenCV
* Haar Cascade classifier
* Webcam / laptop camera
* VS Code or PyCharm
* Python virtual environment

---

## How It Works

The basic computer vision pipeline is:

```text
Camera → frame → grayscale → Haar Cascade detector → face boxes → display result
```

Steps:

1. Open the webcam using OpenCV.
2. Read frames continuously.
3. Convert each frame from BGR to grayscale.
4. Run Haar Cascade face detection.
5. Draw rectangles around detected faces.
6. Display the video window.
7. Press `q` to exit.

---

## Setup

Create a virtual environment:

```bash
python3 -m venv .venv
```

Activate it:

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

---

## Run the Project

```bash
python camera.py
```

Press `q` to close the camera window.

---

## Requirements

The project dependencies are listed in:

```text
requirements.txt
```

Current dependency:

```text
opencv-python
```

---
