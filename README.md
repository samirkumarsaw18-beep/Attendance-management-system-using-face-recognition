
# Face based attendance system using python and openCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/) 

# 🎓 Attendance Management System Using Face Recognition

An intelligent Attendance Management System that uses **Face Recognition** technology to automatically identify students and mark attendance. The system eliminates manual attendance, reduces proxy attendance, and provides an accurate and efficient attendance tracking solution.

---

# 📌 Features

- 📷 Real-time face detection
- 😊 Face recognition using trained dataset
- 📝 Automatic attendance marking
- 📅 Attendance stored with date and time
- 👨‍🎓 Student registration
- 📂 Attendance records in CSV format
- ⚡ Fast and accurate recognition
- 🖥️ User-friendly graphical interface

---

# 🛠️ Technologies Used

- Python
- OpenCV
- Face Recognition
- NumPy
- Pandas
- Tkinter
- CSV
- PIL (Pillow)

---

# 📂 Project Structure

```
Attendance-Management-System/
│── dataset/
│── trainer/
│── images/
│── Attendance/
│── StudentDetails/
│── haarcascade_frontalface_default.xml
│── train.py
│── attendance.py
│── main.py
│── requirements.txt
│── README.md
```

---

# 🚀 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/attendance-management-system.git
```

## 2. Navigate to the Project Folder

```bash
cd attendance-management-system
```

## 3. Create a Virtual Environment (Optional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

## 4. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# ▶️ How to Run

Run the main application:

```bash
python main.py
```

or

```bash
python attendance.py
```

(depending on your project structure)

---

# 📷 How It Works

### Step 1
Register a new student by entering the student details.

### Step 2
Capture multiple face images using the webcam.

### Step 3
Train the face recognition model.

### Step 4
Start face recognition.

### Step 5
The system detects the student's face and automatically marks attendance with the current date and time.

---

# 📊 Output

The attendance is automatically saved in the **Attendance** folder as a CSV file containing:

- Student ID
- Student Name
- Date
- Time
- Attendance Status

---

# 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt
```

Required libraries include:

- opencv-python
- numpy
- pandas
- pillow
- face-recognition

---

# 🌐 Deployment

This is a **Python desktop application**.

GitHub Pages **cannot run Python applications**.

To share the project:

1. Upload the source code to GitHub.
2. Build a Windows executable using PyInstaller.

```bash
pyinstaller --onefile --windowed main.py
```

The executable will be created inside the **dist/** folder.

---

# 📸 Screenshots

Include screenshots of:

- Home Page
- Student Registration
- Face Capture
- Model Training
- Attendance Window
- Attendance Report

---

# 🚀 Future Enhancements

- Cloud-based attendance storage
- Mobile application support
- QR Code integration
- Email notifications
- Real-time dashboard
- Face mask detection
- Emotion detection
- Multiple camera support

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 📄 License

This project is developed for educational and learning purposes.

---

# 👨‍💻 Developer

**Samir Kumar Saw**

MCA Student | Python Developer

GitHub:
https://github.com/samirkumarsaw18-beep

---

⭐ If you found this project helpful, please give it a **Star** on GitHub!
## Just follow me and Star⭐ my repository
