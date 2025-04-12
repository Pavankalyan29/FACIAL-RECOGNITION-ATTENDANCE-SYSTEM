# Facial Recognition Attendance System
## Project Overview
A Python-based automated attendance system that uses **face recognition** to mark student attendance in real-time. The system captures faces via a webcam, compares them with a pre-registered database, and logs attendance in a **CSV file** with timestamps.
## Key Features
**✔ Real-time face detection & recognition** using <code>face_recognition</code> and OpenCV<br>
**✔ Automated CSV logging** with date-wise attendance records<br>
**✔ Simple & efficient** – Works with a webcam or any video input<br>
**✔ Customizable** – Easily add/remove known faces<br>
## 🛠 Technologies Used
- **Python** (Primary language)<br>
- **OpenCV (cv2)** – For video capture and image processing<br>
- **face_recognition** – High-performance face detection & recognition<br>
- **NumPy** – For numerical operations<br>
- **CSV module** – For storing attendance records<br>
## 📂 Project Structure
<pre>
    Facial-Recognition-Attendance-System/
    ├── main.py                 # Main Python script  
    ├── faces/                  # Folder containing known face images  
    │   ├── pavan.jpg           # Sample face 1  
    │   ├── chintu.jpg          # Sample face 2   
    ├── attendance_records/     # (Optional) Auto-generated CSV logs  
    │   └── DD-MM-YYYY.csv      # Example: 12-04-2025.csv  
    └── README.md               # Project documentation
</pre>

## 🚀How to Run the Project?
### Prerequisites
- Python 3.6+
- Install dependencies:
  --- bash
  pip install opencv-python face-recognition numpy
  
### Steps to Execute
1.**Add known faces** in the <code>faces/</code> folder (e.g., <code>pavan.jpg</code>, <code>chintu.jpg</code>).<br>
2.**Run the script:**
<pre>python main.py</pre>
3.**Press** <code>Q</code> to stop the program and save attendance.
## 📷Sample Output
- **Real-time recognition:** Displays "<code>[Name] Present</code>" on detected faces.
- **CSV Log Example:**
<pre>
 Name, Time  
 Pavan, 14:30:45  
 Chintu, 14:31:10  
</pre>
## 📌 Possible Improvements
🔹 **Add a GUI** (Tkinter/PyQt) for easier face registration.<br>
🔹 **Integrate with databases** (SQLite/MySQL) for long-term storage.<br>
🔹 **Deploy as a web app** using Flask/Django.<br>
🔹 **Improve accuracy** with deep learning models (Dlib/CNN).
## 💡 Why This Project?
This system **eliminates manual attendance** and reduces errors, making it useful for **schools, offices, and events**. It demonstrates **Python, OpenCV, and AI integration**—a great addition to your portfolio!
