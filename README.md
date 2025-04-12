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
<pre>
**├── main.py**               # Main Python script  
**├── faces/**                # Folder containing known face images  
**│   ├── pavan.jpg**         # Sample face 1  
**│   ├── chintu.jpg**        # Sample face 2   
**├── attendance_records/**   # (Optional) Auto-generated CSV logs  
**│   └── DD-MM-YYYY.csv**    # Example: 12-04-2025.csv  
**└── README.md**             # Project documentation
</pre>
