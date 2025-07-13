# Face Recognition Based Attendance System 🎓📸

A deep learning-based smart attendance system using face recognition to automate the process of marking student or employee attendance in real-time through live video streaming.

## 🔍 Project Overview

This project leverages computer vision and deep learning to build an automatic attendance management system. It replaces traditional manual or RFID-based methods with a fast and reliable face recognition pipeline using OpenCV, Dlib, and Local Binary Pattern Histograms (LBPH).

## 👨‍💻 Developed By

**Saurabh Prasad**  
Department of Computer Science  
Ramaiah Polytechnic, Bangalore  
📧 saurabhsf6@gmail.com

---

## 📌 Features

- Real-time face detection using OpenCV Haar Cascades
- Facial landmark detection using Dlib
- Image preprocessing (Contrast Adjustment, Histogram Equalization)
- Face recognition with LBPH and SVM
- Attendance logging in CSV format (Name, Date, Time)
- Duplicate prevention (same person not marked twice)
- Easy to deploy and automate

---

## 🧠 Technologies Used

- Python
- OpenCV
- Dlib
- NumPy / Pandas
- CSV file handling
- Local Binary Pattern Histogram (LBPH)
- Histogram of Oriented Gradients (HOG)
- Haar Cascade Classifier

---

## 🔧 How It Works

1. **Image Capture**: A camera captures live video of individuals entering the classroom.
2. **Face Detection**: Detects faces in frames using Haar Cascades and HOG descriptors.
3. **Facial Landmark Estimation**: Identifies key points (eyes, nose, jawline, etc.).
4. **Face Recognition**: Matches detected face with known database using LBPH.
5. **Attendance Logging**: Marks attendance in a CSV file (`attendance.csv`) with a timestamp.
6. **Database Management**: Stores face data of enrolled students during the registration phase.

Install dependencies:

bash
Copy
Edit
pip install opencv-python dlib numpy pandas
Run the system:

bash
Copy
Edit
python attendance_system.py
Make sure your webcam is connected and accessible.

📁 Folder Structure
bash
Copy
Edit
face-recognition-attendance/
├── dataset/              # Stored student face data
├── attendance.csv        # Attendance log file
├── attendance_system.py  # Main script
├── README.md             # Project documentation
└── ...
🎯 Future Improvements
Add GUI using Tkinter or PyQt

Integrate with online dashboards (Flask/Django)

Use deep CNN-based face encodings (e.g., FaceNet)

Send real-time notifications/emails on attendance

OpenCV documentation
Dlib library

<img width="827" height="599" alt="image" src="https://github.com/user-attachments/assets/4b2f4f2d-a610-4667-963f-a9e66afacbff" />
