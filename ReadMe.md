# 📸 Real-Time Face Emotion Detection Application

This repository contains a real-time face emotion detection application using OpenCV, Keras, and a custom CNN model. The application captures images from the webcam, detects faces, and recognizes emotions.

## 📋 Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Models](#models)
- [Requirements](#requirements)
- [License](#license)

## 📥 Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/emotion-recognition.git
    cd emotion-recognition
    ```

2. **Create and activate a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Download and place the required models in the `models` directory:**
    - `emotion_model1.json`
    - `emotion_model1.h5`
    - `haarcascade_frontalface_default.xml`

## ▶️ Usage

1. **Run the application:**
    ```bash
    python app.py
    ```

2. The application will open a webcam preview window. You can:
    - Press `c` to capture an image and recognize the emotion.
    - Press `q` to quit the application.

3. Captured images and detected emotions will be saved as:
    - `result_image.png`: Captured image with detected face and emotion.
    - `emotion_recognition.txt`: Detected emotion text file.

## 📂 Project Structure

```plaintext
emotion-recognition/
│
├── models/
│   ├── emotion_model1.json
│   ├── emotion_model1.h5
│   └── haarcascade_frontalface_default.xml
│
├── requirements.txt
├── app.py
├── README.md
└── .gitignore
```

## Models
Ensure you have all the model files
Make sure to add emotion_model.h5 to models

## Requirements
Ensure you have the dependencies installed. You can install them using the requirements.txt file.

### How to Save the README

1. **Save the content above in a file named `README.md`.**
2. **Place the `README.md` file in the root directory of your GitHub repository.**

### Additional Recommendations

- **Update the `git clone` URL** to your actual repository URL.
- **Replace `your_script_name.py`** with the actual name of your Python script file.
- **Customize any sections** as needed to fit your project and preferences better.

