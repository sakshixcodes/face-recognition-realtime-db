# 👤 Face Recognition using Real-Time Database

This project performs real-time face recognition using OpenCV and stores recognized faces in a real-time database like Firebase. Ideal for attendance systems or security verification applications.

## 🚀 Features

- Real-time webcam face detection & recognition
- Face encoding using `face_recognition` library
- Stores recognized faces in Firebase Realtime DB
- Can trigger events on successful identification (e.g., mark attendance)

## 🧠 Technologies Used

- Python
- OpenCV
- face_recognition
- Firebase (Pyrebase)
- Streamlit or Tkinter (optional UI)
- NumPy, pickle

## 🗂️ Project Structure
├── trained_faces/ # Directory of known face encodings
├── app.py # Main face recognition app
├── encode_faces.py # Preprocessing script for known faces
├── firebase_config.json # Firebase credentials
├── requirements.txt
└── README.md


---

## 🎥 How it Works

1. Known faces are encoded and saved using `encode_faces.py`
2. `app.py` captures webcam input, detects faces, compares with saved encodings
3. Matches are logged to a Firebase Realtime Database

---

## 🔗 Firebase Setup

1. Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
2. Enable Realtime Database & get credentials
3. Paste your Firebase config into `firebase_config.json`

---

## 📦 Run Locally

```bash
git clone https://github.com/your-username/face-recognition-realtime-db
cd face-recognition-realtime-db
pip install -r requirements.txt
python app.py


🙋‍♀️ About Me
Hi, I’m Sakshi Bhandari, a student of AI & Data Science.
This project showcases the application of facial recognition in security and automation using machine learning.

MIT License
Copyright (c) 2025 Sakshi Bhandari

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

