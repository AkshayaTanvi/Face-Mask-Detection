# Face Mask Detection

Real-time face mask detection using Deep Learning and OpenCV.

## Overview

This project uses a Convolutional Neural Network (CNN) to detect whether a person is wearing a mask or not in real-time video streams. The model is trained to differentiate between images with and without face masks and integrated with OpenCV to enable live detection through a webcam.

## Features

- Real-time face mask detection on video streams
- High accuracy with trained CNN model
- Uses deep learning with TensorFlow and Keras
- Face detection using OpenCV and a pre-trained face detector
- Clean, modular, and well-documented code

## Tech Stack

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Imutils

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AkshayaTanvi/Face-Mask-Detection.git
   cd Face-Mask-Detection

2. **Create and Activate Virtual Environment** (Optional but Recommended)


python -m venv venv

# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

3. **Install Dependencies**
```b   
pip install -r requirements.txt
```
## Usage
To run real-time mask detection using your webcam:

python detect_mask_video.py

This will:

Access your webcam feed

Detect faces in real-time

Predict if each detected face has a mask or not

Display results with bounding boxes and labels

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

