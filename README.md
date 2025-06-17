
# PRAYUJ - Smart Traffic Management System 🚦 (HackDiwas 2.0 runners-up)

**PRAYUJ** is an intelligent traffic management interface developed as a mini-project for the B.Tech 2nd Year curriculum at United University. It utilizes real-time image processing and Google Cloud Vision API for vehicle detection, number plate recognition, and traffic violation logging (such as red-light crossing or overspeeding).

## 👥 created by:-

- **Alok Mishra**

## 🧠 Supervisor

- **Mr. Kuldeep Singh**  
Faculty, United University

---

## 🔧 Features

- 🎥 **Live Webcam Integration** for real-time monitoring
- 🧠 **Google Cloud Vision API** for:
  - Vehicle Detection
  - Number Plate Recognition
- 🚨 **Violation Detection**
  - Red Light Jumping
  - Overspeeding
- 💸 **Fine Management System** stored in local database (file-based)
- 🗺️ **Interactive Interface** includes:
  - Live camera feed
  - Traffic light status and controls
  - Location map
  - Graphical analytics
  - Authority dashboard

---

## 🛠️ Tech Stack

- Python (Backend & Image Processing)
- Tkinter (GUI)
- Google Cloud Vision API
- OpenCV (Camera Feed Processing)
- SQLite / CSV (Local DB)
- PIL (Image Handling)
- Matplotlib (Graph Generation)

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/prayuj-traffic-system.git
cd prayuj-traffic-system
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Setup Google Cloud Vision
- Create a project on [Google Cloud Console](https://console.cloud.google.com/)
- Enable **Vision API**
- Download service account key (`.json` file) and set environment variable:

```bash
export GOOGLE_APPLICATION_CREDENTIALS="your-key-file.json"
```

### 4. Run the Project
```bash
python main.py
```

---

## 📸 Screenshots

_Add interface screenshots here once ready_

---

## 📁 Project Structure

```
prayuj-traffic-system/
│
├── main.py                # Main GUI application
├── camera_module.py       # Webcam and frame capture
├── vision_api.py          # Google Cloud Vision functions
├── violation_checker.py   # Logic for traffic violation detection
├── fine_database.csv      # Local fine database
├── utils/                 # Utility functions (plate detection, etc.)
├── assets/                # Images/icons used in GUI
└── README.md              # This file
```

---

## 📝 License

This project is for educational use only.

---

## 📬 Contact

For any queries, feel free to reach out:

- **Mayank Mishra** - mayank@example.com
- **Abdullah Khan** - abdullah@example.com
