# ⚡ Replica — Clone Website Detection System  
A machine-learning based clone & phishing website detection system that analyzes URLs and identifies whether a website is **legitimate** or **malicious**.  
Built using **Python, Flask API, XGBoost**, and integrated with a **browser extension** for real-time detection.

---

## 📌 Overview  
Replica is a clone website detection tool that works by analyzing URL patterns and predicting if the received link is suspicious.  
The backend model classifies every incoming URL as:

- 🟢 **Legitimate Website**  
- 🔴 **Fake / Clone / Phishing Website**

If a website is detected as fake, the system **automatically redirects the user to the real website**.

Replica does **not** allow manual URL entry — it detects URLs automatically through user interaction and browser extension monitoring.

---

## 🚀 Features  

### 🔍 Automatic URL Detection  
The browser extension captures and sends URLs automatically whenever the user visits a website.

### 🧠 Machine Learning Detection (XGBoost Based)  
Replica uses an **XGBoost classifier** trained on phishing + legitimate URLs  
*(not AI-powered — purely ML-based)*.

### 🛡 Real-Time Classification  
Flask API instantly returns:  
- `legitimate`  
- `malicious`  

### 🔗 Auto-Redirect System  
When a URL is flagged as malicious, Replica redirects the user to the safe website.

### 📝 Pop-Up Notification  
The browser extension displays:  
- 🟢 *This is a real website*  
- 🔴 *Fake website — redirecting to real site*  

### 💾 Dataset Used  
- `malicious_phish.csv`  
- `legitimate-urls.csv`  

---

## 🏗️ Project Structure  

Replica/
│── app.py # Flask backend API
│── model/
│ └── xgboost_model.pkl # Trained XGBoost model
│── extension/ # Browser extension files
│ ├── manifest.json
│ ├── popup.html
│ ├── popup.js
│ ├── background.js
│── static/
│── templates/
│── datasets/
│ ├── malicious_phish.csv
│ ├── legitimate-urls.csv
│── README.md

---

## ⚙️ Technologies Used  

- **Python**
- **Flask (REST API)**
- **XGBoost (Machine Learning)**
- **HTML, CSS, JavaScript** (Browser Extension)
- **MongoDB** (optional user tracking)

---

## 🔌 How Replica Works  

### **1️⃣ Browser Extension Monitors URLs**
Automatically sends visited URLs to the backend.

### **2️⃣ Flask Extracts Features**
Examples:
- URL length  
- Number of dots  
- Hyphens  
- Suspicious keywords  
- Use of IP address  

### **3️⃣ Model Predicts Using XGBoost**
Returns:
- `0` → Legitimate  
- `1` → Malicious / Clone / Phishing  

### **4️⃣ Notification + Auto Redirect**
If malicious → user is redirected to the safe legitimate site.

---

## ▶️ Running the Project  

### **Step 1 — Install Dependencies**
pip install -r requirements.txt


### **Step 2 — Start the Flask Server**

### **Step 3 — Add Browser Extension**
Chrome → Extensions → Turn on **Developer Mode** →  
**Load Unpacked** → Select the `extension/` folder.

---

## 👨‍💻 Developer  
**Dharsana K R**  
Full Stack Developer | Cybersecurity Enthusiast

---


