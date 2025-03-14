<h1 align="center"> ANPR And ATCC For Smart Traffic Management</h1>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Infosys-Springboard-brightgreen.svg" alt="Infosys Springboard">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg" alt="Status">
</p>

<p align="center">
  <img src="https://cdn.prod.website-files.com/6479eab6eb2ed5e597810e9e/6749ca696ac206d7c58802c6_Traffic_Thumbnail%202.png" alt="Project Banner">
</p>

## Overview
This project is a **real-world traffic violation detection system** built using **Flask** for the backend and **HTML, CSS, and JavaScript** for the frontend. It processes video footage to detect various traffic violations, including:
- **ATCC**(Automatic Traffic Classication and control)
- **Heat Map Visualisation** (Specifies high of lane on the road)
- **Helmet violations** (detects if a rider is not wearing a helmet)
- **Triple riding** (detects if more than two people are riding a motorbike)
- **Number plate recognition** (to be implemented in the future)

The system leverages **YOLO (You Only Look Once) models** for object detection and processes videos dynamically to provide real-time insights on traffic violations.

---

## Features
- **Video Upload**: Users can upload a video of traffic footage.
- **Real-time Processing**: The system analyzes the video and detects violations.
- **Helmet Detection**: Identifies riders not wearing helmets.
- **Triple Riding Detection**: Counts the number of riders on a bike and flags violations.
- **Dynamic Results**: Displays detected violations with bounding boxes.


---

## Tech Stack
### Backend:
- **Flask** (Python framework for API handling)
- **OpenCV** (for video processing)
- **YOLOv8** (for object detection)

### Frontend:
- **HTML, CSS, JavaScript** (for UI/UX)
- **AJAX/Fetch API** (to interact with Flask backend)

---

---

## Installation
### Step 1: Clone the Repository
```sh
git clone 
```

### Step 2: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 3: Run the Flask Backend
```sh
cd backend
python app.py
```
**Expected Output:**
```
 * Running on http://127.0.0.1:5000/
```

### Step 4: Run the Frontend
Open `index.html` in a browser or use Live Server if using VS Code.

---

## Usage
1. **Upload a Video**: Select a traffic footage file from your system.
2. **Click Process**: The system processes the video and detects violations.
3. **View Results**: Detected violations are displayed with bounding boxes.

---

## API Endpoints
- `POST /upload` → Accepts a video file for processing.
- `GET /results` → Returns detected violations as JSON.

---

## Future Enhancements
✅ Number Plate Recognition (OCR for vehicle identification)
✅ Improved UI for better user experience
✅ Deployment on a cloud server

---

## Contributors
- **Your Name** (Developer)
- **Your Team Members (if any)**

---

## License
MIT License

---

🚀 **Start detecting traffic violations today!**
