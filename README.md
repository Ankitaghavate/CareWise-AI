# 🚑 CareWise AI – Ambulance Tracking System

CareWise AI – Ambulance Tracking System is a web-based application designed to reduce emergency medical response time by enabling **real-time ambulance tracking and route optimization** using geolocation services and web technologies.

The system allows users to request the nearest available ambulance and helps administrators manage ambulance data efficiently.

---

## 🎯 Problem Statement

In emergency medical situations, delays in locating and dispatching ambulances can result in critical consequences. Existing systems often lack real-time tracking and optimized routing, leading to slower response times.

---

## 💡 Solution Overview

CareWise AI provides:
- Real-time visualization of ambulance locations on a live map  
- Fast and optimized routing to user locations  
- Centralized ambulance and request management  

---

## 🛠️ Technology Stack

### Frontend
- HTML  
- CSS  

### Backend
- PHP  
- MySQL  
- Apache (XAMPP)

### API & Tools
- Google Maps API  
- XAMPP (Local Server)

---

## ⚙️ System Architecture

1. User logs into the system  
2. User requests an ambulance by providing location  
3. System fetches ambulance data from the database  
4. Google Maps API displays live ambulance locations  
5. Shortest route is calculated and shown  
6. Admin manages ambulance and user information  

---

## ✨ Features

- 🚨 Real-time ambulance tracking  
- 🔐 Secure user and admin authentication  
- 📍 Nearest ambulance detection  
- 🗺️ Live map and route optimization  
- 🧑‍💼 Admin dashboard for management  
- 📱 Responsive web interface  

---

## 🧪 Testing

- Unit testing of login, tracking, and database modules  
- Integration testing between frontend, backend, and database  
- User acceptance testing for usability and accuracy  

---

## ⚠️ Challenges Faced

- Google Maps API integration  
- Handling multiple database requests  
- Ensuring responsive UI across devices  

### Solutions
- Followed official API documentation  
- Optimized database queries  
- Implemented responsive CSS techniques  

---

## 🚀 Future Enhancements

- Mobile application support (Android & iOS)  
- AI-powered route optimization using traffic data  
- Multi-language interface  
- Extension to other emergency services  

---

## 🚀 Getting Started

Follow these instructions to get the project up and running on your local machine.

### 1. Prerequisites
* [XAMPP](https://www.apachefriends.org/index.html) (Apache & MySQL)
* Web Browser (Chrome, Firefox, etc.)

### 2. Move Project to XAMPP
Copy the project folder to your local XAMPP directory:
- **Path:** `xampp/htdocs/`

### 3. Start Server
1.  Open the **XAMPP Control Panel**.
2.  Start **Apache**.
3.  Start **MySQL**.

### 4. Database Setup
1.  Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
2.  Create a new database (e.g., `ambulance_tracking`).
3.  Click the **Import** tab and upload the provided `.sql` file from the project root.

### 5. Run the Project
Open your browser and navigate to:
> [http://localhost/carewise-ai-ambulance-tracking/](http://localhost/carewise-ai-ambulance-tracking/)

---

## 📂 Project Structure
```text
carewise-ai-ambulance-tracking/
├── assets/           # CSS, JS, and Images
├── config/           # Database connection files
├── database/         # .sql import files
├── screenshots/      # UI Previews
├── index.php         # Main landing page
└── README.md         # Documentation
