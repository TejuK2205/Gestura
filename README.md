# Gestura
This repository contains a real-time sign language gesture recognition system built with Convolutional Neural Networks (CNN). The project utilizes a trained CNN model to recognize and classify gestures corresponding to digits (0-9), uppercase letters (A-Z), and spaces. The system captures video from a webcam and overlays the predicted gesture on the video feed.

## Features

- Real-time gesture recognition using a CNN model
- Webcam-based input with overlay of predicted gestures
- Supports gestures for digits, uppercase letters, and space
- Preprocessing pipeline for resizing and normalizing images

## Technologies Used

- **Python**: Programming language
- **OpenCV**: Computer vision library for video capture and image processing
- **NumPy**: Library for numerical operations
- **TensorFlow/Keras**: Deep learning framework for training and loading the CNN model

## Installation

To set up the project environment and install the necessary dependencies, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/gestura.git
    cd sign-language-detection
    ```

2. **Create and Activate a Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```


3. **Download and Place the Trained Model**

   Ensure that you have the trained model file (e.g., `cnn_model.h5`). Place it in the project directory.

## Usage

To start the real-time gesture recognition, run the provided script:

```bash
python MAIN_FILE_CNN.ipynb
```

The system will display the predicted gesture on the video feed from your webcam. Press 'q' to exit the application.

Project Structure
```plaintext
detect_gesture.py: Main script to run real-time gesture recognition.
requirements.txt: List of dependencies.
gesture_model.h5: Trained CNN model (ensure this file is present in the project directory).
```
