# Facial-Recognition-Attendance-System

This project demonstrates how to create a facial recognition attendance system using Python. Leveraging libraries such as OpenCV, Numpy, and face_recognition, this system uses facial recognition to mark attendance, providing a practical application of machine learning and computer vision techniques.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to use facial recognition as an authentication mechanism for an attendance system. The system captures images from a webcam, recognizes known faces, and marks their attendance by recording the time they were recognized.

## Features

- Real-time face detection and recognition using OpenCV and face_recognition.
- Attendance marking and logging in a CSV file.
- Simple graphical user interface (GUI) for starting and stopping the recognition process.
- Easy configuration and setup.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/facial-recognition-attendance-system.git
   cd facial-recognition-attendance-system
   ```

2. **Install the required packages:**
   ```bash
   pip install opencv-python numpy face_recognition
   ```

## Usage

1. **Prepare the images:**
   - Save the images of the individuals to be recognized in a folder named `photos`.
   - Ensure the images are named appropriately (e.g., `JAY.jpg`, `AMAN.jpg`).

2. **Run the script:**
   ```bash
   python facial_attendance_system.ipynb
   ```

3. **Use the GUI:**
   - Click the "Start" button to begin the recognition process.
   - Click the "Stop" button to end the recognition process.

4. **Check the attendance log:**
   - A CSV file with the current date will be created, logging the attendance times.

## Project Structure

```
facial-recognition-attendance-system/
│
├── photos/                     # Directory for storing known face images
│   ├── JAY.jpg
│   ├── AMAN.jpg
│   ├── AYUSHI.jpg
│   └── SANAYA.jpg
│
├── attendance_system.py        # Main script for running the attendance system
├── README.md                   # Project documentation
└── requirements.txt            # List of dependencies
```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. Make sure to follow the project's code style and include appropriate tests for your modifications.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
