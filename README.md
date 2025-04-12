# Facial Recognition Attendance System
## Project Overview
A Python-based automated attendance system that uses **face recognition** to mark student attendance in real-time. The system captures faces via a webcam, compares them with a pre-registered database, and logs attendance in a **CSV file** with timestamps.
## Key Features
**✔ Real-time face detection & recognition** using face_recognition and OpenCV<br>
**✔ Automated CSV logging** with date-wise attendance records<br>
**✔ Simple & efficient** – Works with a webcam or any video input<br>
**✔ Customizable** – Easily add/remove known faces<br>
## 🛠 Technologies Used
***Python** (Primary language)<br>
***OpenCV (cv2)** – For video capture and image processing<br>
***face_recognition** – High-performance face detection & recognition<br>
***NumPy** – For numerical operations<br>
***CSV module** – For storing attendance records<br>
## 📂 Project Structure
### Facial-Recognition-Attendance-System/ ###
**├── main.py**&nbsp&nbsp&nbsp            # Main Python script  
**├── faces/**&nbsp&nbsp&nbsp                # Folder containing known face images  
**│   ├── pavan.jpg**&nbsp&nbsp         # Sample face 1  
**│   ├── chintu.jpg**&nbsp&nbsp        # Sample face 2   
**├── attendance_records/**&nbsp   # (Optional) Auto-generated CSV logs  
**│   └── DD-MM-YYYY.csv**&nbsp    # Example: 12-04-2025.csv  
**└── README.md**&nbsp&nbsp&nbsp            # Project documentation  
