
---

# 🆔 Smart Aadhaar Center Monitoring & Analytics System

### UIDAI Data Hackathon 2026

A cloud-based, real-time monitoring and analytics platform designed to improve transparency, efficiency, and decision-making in Aadhaar enrollment and update centers.

---

## 📌 Project Overview

The **Smart Aadhaar Center Monitoring & Analytics System** digitizes the complete Aadhaar center workflow — from application submission to final status update — and provides real-time insights using dashboards and analytics.

The system introduces:

* Centralized monitoring
* Role-based access (Operator, Admin, Public)
* Real-time status tracking
* Failure-reason analytics for incomplete applications
* Public, read-only transparency dashboard

This project aligns with **UIDAI’s vision of smart governance and data-driven decision making**.

---

## 🎯 Key Features

### 👨‍💼 Operator Module

* Secure login
* Submit Fresh Aadhaar & Update applications
* Automatic timestamping
* Status set to *Pending*

### 🛠 Admin Module

* Secure admin authentication
* View all applications
* Mark applications as **Done / Not Done**
* Select standardized failure reasons:

  * Fingerprint sensor not working
  * Iris sensor not working
  * Camera not working
  * Incomplete document
* Save remarks & applicant contact number

### 📊 Public Dashboard

* No login required
* Read-only access
* Real-time metrics:

  * Total Applications
  * Pending
  * Done
  * Not Done
* **Pie chart analytics** showing why applications are not completed
* Auto-updating live data

---

## 📈 Analytics & Insights

* Real-time application statistics
* Failure reason distribution (pie chart)
* Helps identify:

  * Faulty biometric devices
  * Documentation issues
  * Operational bottlenecks
* Enables proactive maintenance & planning

---

## 🏗 System Architecture

```
Operator / Admin / Public User
            |
            v
   Web Frontend (HTML, CSS, JS)
            |
            v
 Google Apps Script (REST API)
            |
            v
     Google Sheets (Cloud DB)
```

---

## 🛠 Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Chart.js (Data Visualization)

### Backend

* Google Apps Script (Serverless REST API)

### Database

* Google Sheets (Cloud-based)

### Hosting

* Google Apps Script Web App
* GitHub Pages

---

## 🔐 Authentication Details (Demo)

### Operator Login

```
Username: operator01
Password: aadhaar123
```

### Admin Login

```
Username: admin
Password: admin123
```

---

## 🌐 Live Demo Links

> ⚠️ Replace `<your-username>` and `<repo-name>` after deployment

### 👨‍💼 Operator Portal

```
https://mohammadzakariya07.github.io/12/index.html
```

### 🛠 Admin Panel

```
https://mohammadzakariya07.github.io/12/admin.html
```

### 📊 Public Dashboard (Read-Only)

```
https://mohammadzakariya07.github.io/12/public-dashboard.html
```

---

## 📂 Repository Structure

```
📁 smart-aadhaar-system
│
├── index.html              # Operator login & application submission
├── dashboard.html          # Operator dashboard
├── admin.html              # Admin panel
├── public-dashboard.html   # Public analytics dashboard
│
├── script.js               # Frontend logic
├── dashboard.js            # Session & dashboard logic
├── style.css               # Styling
│
├── Code.gs                 # Google Apps Script backend
└── README.md               # Project documentation
```

---

## 🚀 How to Deploy

1. Deploy backend using **Google Apps Script**
2. Set access to **Anyone**
3. Copy Web App URL
4. Update frontend `SCRIPT_URL`
5. Host frontend on **GitHub Pages**
6. Access dashboards via browser

---

## 🔮 Future Enhancements

* ESP32 + OLED/LCD live display
* Automated alerts for sensor failures
* Daily / weekly analytics
* SMS & email notifications
* AI-based failure prediction
* Mobile app integration

---

## 🧠 Use Cases

* Aadhaar Enrollment Centers
* UIDAI Monitoring Teams
* Smart Governance Platforms
* Control Rooms
* Large-scale biometric systems

---

## 👤 Developer Details

**Mohammad Zakariya**
B.Tech – Electronics & Communication Engineering

📞 **Mobile:** 9560643353
📧 **Email:** [mzakariya0007@gmail.com]

🌐 **Portfolio:**
[https://mohammadzakariya07.github.io/portfolio](https://mohammadzakariya07.github.io/portfolio)

💼 **LinkedIn:**
[https://www.linkedin.com/in/mohammad-zakariya](https://www.linkedin.com/in/mohammad-zakariya)

💻 **GitHub:**
[https://github.com/mohammadzakariya07](https://github.com/mohammadzakariya07)

---

## 📌 License

This project is developed for **UIDAI Data Hackathon 2026** and is intended for **educational, research, and demonstration purposes**.

---
