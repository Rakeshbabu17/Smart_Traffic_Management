<h1 align="center"> ANPR And ATCC For Smart Traffic Management</h1>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Infosys-Springboard-brightgreen.svg" alt="Infosys Springboard">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg" alt="Status">
</p>

<p align="center">
  <img src="https://cdn.prod.website-files.com/6479eab6eb2ed5e597810e9e/6749ca696ac206d7c58802c6_Traffic_Thumbnail%202.png" alt="Project Banner">
</p>

## 🌟 Overview
This project is a **real-world traffic violation detection system** built using **Flask** for the backend and **HTML, CSS, and JavaScript** for the frontend. It processes video footage to detect various traffic violations, including:
- **ATCC**(Automatic Traffic Classication and control)
- **Heat Map Visualisation** (Specifies high of lane on the road)
- **Helmet violations** (detects if a rider is not wearing a helmet)
- **Triple riding** (detects if more than two people are riding a motorbike)
- **Number plate recognition** (to be implemented in the future)

The system leverages **YOLO (You Only Look Once) models** for object detection and processes videos dynamically to provide real-time insights on traffic violations.

---

## ✨ Features
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

## 🛠 Installation
### Step 1: Clone the Repository
```sh
git clone https://github.com/Rakeshbabu17/Smart_Traffic_Management.git 
```

### Step 2: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 3: Run the Flask Backend
```
python app.py
```
**Expected Output:**
```
 * Running on http://127.0.0.1:5000/
```

### Step 4: Run the Frontend
 `npm run dev`

---

## 🚀 Usage
1. **Upload a Video**: Select a traffic footage file from your system.
2. **Click Process**: The system processes the video and detects violations.
3. **View Results**: Detected violations are displayed with bounding boxes.

---
## 📈 Results

https://github.com/user-attachments/assets/a89ae7d5-4f3d-4b43-b1c6-872949bb3d7e



---
## 📄 License
This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.
---
<p align="center">
  Made with ❤️ by the Infosys Springboard Internship Team
</p>

