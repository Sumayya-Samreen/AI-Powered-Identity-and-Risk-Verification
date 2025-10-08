
# AI Face Recognition Attendance System

## Overview
This project is an AI-powered face recognition system built in Python using OpenCV and the `face_recognition` library.
It contains two main functionalities:

1. **Face Matching (`main.py`)** – Compares a test image with a reference image to determine if they match.
2. **Attendance System (`attendance.py`)** – Detects faces in real-time via webcam and marks attendance for recognized faces.

This project can be useful for secure identity verification, automated attendance tracking, and face-based access control systems.

## Features
- ✅ Real-Time Face Recognition using webcam feed.
- ✅ Image-to-Image Face Matching for identity verification.
- ✅ Multiple Faces Handling for attendance.
- ✅ Relative File Paths for portability.
- ✅ Encoding Known Faces once for efficiency.
- ⚡ Lightweight & Fast using optimized face recognition methods.

## Installation

### Prerequisites
- Python 3.11+
- pip
- Git

### Clone the Repository
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

### Create Virtual Environment
```bash
python -m venv .venv
```

### Activate Virtual Environment
**Windows PowerShell:**
```powershell
.venv\Scripts\Activate.ps1
```

**Windows CMD:**
```cmd
.venv\Scripts\activate.bat
```

**Linux/macOS:**
```bash
source .venv/bin/activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage

### 1. Face Matching
```bash
python main.py
```

### 2. Attendance System
```bash
python attendance.py
```

## Folder Structure
```
project-folder/
│
├── images/
│   ├── ElonMusk.jpg
│   ├── Elon_Musk.jpg
│   └── ...
│
├── main.py
├── attendance.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Suggested Future Improvements
- 📄 Attendance Logs – Save attendance records to a CSV file.
- 📸 Snapshot Capture – Automatically capture images for unknown faces.
- 🔐 Security Features – Add authentication and encryption.
- 🎯 Performance Optimization – Use GPU acceleration.
- 🌐 Web Interface – Create a dashboard.
- 📱 Mobile Integration.

## Troubleshooting
- **Camera Not Working:** Try changing camera index in `cv2.VideoCapture()`.
- **Missing Modules:** Run `pip install -r requirements.txt`.
- **Face Recognition Errors:** Ensure clear, frontal face images.

## Pro Tip for Recruiters / Collaborators
This project showcases a practical AI pipeline involving face detection, real-time recognition, and identity verification, making it a strong example of computer vision applications for attendance tracking and security systems.

## Author
**Sumayya — M.Sc. in Artificial Intelligence**
Focused on developing practical AI solutions for real-world computer vision applications, particularly in identity verification and automated systems.
