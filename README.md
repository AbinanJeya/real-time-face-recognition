# Real-Time Face Recognition Attendance System

## Overview
This project is a **real-time attendance system** using Python, OpenCV, and the `face_recognition` library.  
It detects and recognizes faces from a webcam feed and automatically logs attendance in a CSV file.

---


## Features
- Real-time face detection and recognition  
- Automatic attendance logging with timestamp  
- Works with multiple known faces  
- Displays live webcam feed with rectangles and names  

---

## Requirements
- Python 3.x  
- Libraries:

- pip install opencv-python
- pip install face_recognition
- pip install numpy
- pip install dlib



---


##How to Run

Add images of known people to the ImagesAttendance folder.
Name the images with the person's name, e.g., JohnDoe.jpg.
Open a terminal and navigate to the project folder.

Run the script:

python face_attendance.py

A webcam window will open. Detected faces will have a rectangle and name label.
Attendance will be recorded in Attendance.csv with name and timestamp.

##How It Works:

1. Load known images → The program reads all images from the ImagesAttendance folder.

2. Encode faces → Each face is converted into a unique numerical vector (face encoding).

3. Webcam detection → Continuously reads frames from the webcam.

4. Face recognition → Detected faces are compared with known face encodings.

5. Attendance logging → If a face is recognized for the first time, it is recorded in Attendance.csv.


6. Results 

![Webcam Detection](Results.png)



