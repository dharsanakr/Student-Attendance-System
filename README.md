# 📘 Student Attendance WebApp  
A lightweight and user-friendly **attendance management system** built using **Python, Flask, HTML, CSS, and JavaScript**.  
This project allows teachers/admins to add students, mark attendance, and track daily records easily.

---

## 📌 Overview  
The **Student Attendance WebApp** helps manage attendance digitally with a clean interface and simple workflow.  
Users can:

- 🧑‍🎓 **Add Student Details**  
- 🟢 **Mark Present** / 🔴 **Mark Absent**  
- 📅 **View Attendance Records**  
- 💾 **Store Records Securely in Database**

The system aims to replace manual attendance sheets with a digital solution.

---

## 🚀 Features  

### 📝 Add & Manage Students  
Add new students with their details and maintain an updated student list.

### 🔔 Attendance Marking System  
Mark daily attendance with a simple and clean UI:
- 🟢 Present  
- 🔴 Absent  

### 📊 Attendance Records  
View all attendance logs date-wise or student-wise.

### 💾 Database Support  
The backend supports:  
- **MongoDB**, or  
- **SQLite / MySQL**  
(whichever you used in your project)

### 🌐 Clean Frontend UI  
Built using **HTML, CSS, JavaScript** with responsive layout.

---

## 🏗️ Project Structure  

Student-Attendance-WebApp/
│── app.py # Flask backend
│── templates/
│ ├── index.html # Home page
│ ├── add_student.html # Student entry page
│ ├── attendance.html # Mark attendance page
│ └── records.html # View attendance logs
│── static/
│ ├── css/
│ ├── js/
│ └── images/
│── database/ # MongoDB or SQLite data
│── requirements.txt
│── .gitignore
│── README.md

---

## ⚙️ Technologies Used  

- **Python**  
- **Flask**  
- **HTML, CSS, JavaScript**  
- **MongoDB / SQLite / MySQL** (as backend database)

---

## 🔌 How the System Works  

### **1️⃣ Add Students**
Teacher/admin enters student details such as:
- Name  
- Roll Number  
- Class / Section  

### **2️⃣ Mark Attendance**
Daily attendance is marked manually using the web interface:
- 🟢 Present  
- 🔴 Absent  

### **3️⃣ Records Stored in DB**
Attendance is saved in the database with:
- Timestamp  
- Student ID  
- Attendance status  

### **4️⃣ View Attendance**
Admin can view:
- Daily attendance  
- Individual student records  
- History of attendance  

---

## ▶️ Running the Project  

### **Step 1 — Install Dependencies**
pip install -r requirements.txt


### **Step 2 — Run Flask Server**
python app.py


### **Step 3 — Open Browser**
Go to:


http://127.0.0.1:5000

---

## 👩‍💻 Developer  
**Dharsana K R**  
Full Stack Developer | Cybersecurity Enthusiast  

---

