# Make sure to add model- emotion_model.h5 
# Real-Time Face Emotion Detection Application

This repository contains a real-time face emotion detection application using OpenCV, Keras, and a pre-trained deep learning model. The application captures images from the webcam, detects faces, and recognizes emotions.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Models](#models)
- [Requirements](#requirements)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/emotion-recognition.git
    cd emotion-recognition
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download and place the required models in the `models` directory:
    - `emotion_model1.json`
    - `emotion_model1.h5`
    - `haarcascade_frontalface_default.xml`
    - 'emotion_model.h5'

## Usage

1. Run the application:
    ```bash
    python your_script_name.py
    ```

2. The application will open a webcam preview window. You can:
    - Press `c` to capture an image and recognize the emotion.
    - Press `q` to quit the application.

3. Captured images and detected emotions will be saved as:
    - `result_image.png`: Captured image with detected face and emotion.
    - `emotion_recognition.txt`: Detected emotion text file.
