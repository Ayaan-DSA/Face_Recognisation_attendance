# Full Stack Face Recognition Attendance System

A full stack attendance management system built using Flask, Python, OpenCV, HTML, CSS, and JavaScript. The system uses face recognition technology to automatically identify users and mark attendance through a responsive web interface.

---

## Features

- User-friendly web interface
- Face registration using webcam
- Real-time face recognition
- Automatic attendance marking
- Attendance management system
- Machine learning based face detection
- Flask backend integration
- Responsive frontend UI

---

## Tech Stack

### Frontend
- HTML
- CSS


### Backend
- Flask
- Python

### Computer Vision / Machine Learning
- OpenCV
- NumPy

---

## Project Structure

```bash
Face_Recognition_attendance/
│
├── templates/
├── __pycache__/
├── app.py
├── face.xml
├── models.py
├── recognize_face.py
├── register_face.py
├── train_model.py
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Ayaan-DSA/Face_Recognition_attendance.git
cd Face_Recognition_attendance
```

---

## Create Virtual Environment (Optional)

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

Open your browser and visit:

```bash
http://127.0.0.1:5000
```

---

## How It Works

### 1. Face Registration

Users register their faces through the web interface using a webcam. The captured images are stored for training the recognition model.

### 2. Model Training

The system processes the captured face data and trains the machine learning model using OpenCV.

```bash
python train_model.py
```

### 3. Face Recognition

When a user appears in front of the webcam, the system detects and recognizes the face in real time.

```bash
python recognize_face.py
```

### 4. Attendance Marking

After successful recognition, attendance is automatically recorded and managed through the backend system.

---

## Requirements

- Flask
- OpenCV
- NumPy
- Pandas

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---


## License

This project is open source and available under the MIT License.
