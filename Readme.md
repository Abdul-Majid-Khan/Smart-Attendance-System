# Face Recognition Attendance System

This project is a face recognition-based attendance system using Python, OpenCV, and face_recognition library. It captures video from the webcam, recognizes faces, and logs the attendance in a CSV file.

## Features

- Real-time face detection and recognition.
- Automatic logging of attendance with timestamps.
- Easily extendable to add more known faces.

## Prerequisites

- Python 3.x
- OpenCV
- face_recognition library
- numpy
- datetime
- csv
- os

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/face-recognition-attendance-system.git
    cd face-recognition-attendance-system
    ```

2. **Install the required packages:**
    ```bash
    pip install opencv-python
    pip install face_recognition
    pip install numpy
    ```

3. **Add known face images:**
    - Place the images of the known individuals in the `photos` directory.
    - Update the script to load these images and their encodings.

## Usage

1. **Run the script:**
    ```bash
    python attendance_system.py
    ```

2. **Functionality:**
    - The system will start the webcam and begin detecting faces.
    - Recognized faces will be marked as present, and their names along with the current time will be logged in a CSV file named with the current date.
