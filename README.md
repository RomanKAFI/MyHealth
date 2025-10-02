# MyHealth — Virtual Medical Cabinet

Java-based application for managing personal health records, appointments, and treatment tracking.  
Built as a practice project to demonstrate full-stack development concepts and modular design.

---

## 🚀 Overview
MyHealth is a prototype of an eHealth system.  
It simulates how patients can track their medical information, manage appointments, and view basic analytics.  

Key focuses:
- OOP and modular design in Java
- Database-driven application
- Patient records & appointments
- Treatment tracking with a "To-Do" style module
- Future expansion to REST API + GUI

---

## 🛠 Tech Stack
- **Backend:** Java 17 (OOP, Collections, Streams)  
- **Database:** MySQL / PostgreSQL (planned)  
- **UI:** CLI (console), JavaFX (planned)  
- **Practices:** OOP, data persistence, error handling, unit testing  

---

## 📂 Features
- Create / update patient profiles  
- Store medical history (diagnoses, prescriptions)  
- Appointment scheduling  
- Treatment tracking (medications, measurements, tasks)  
- Export simple reports (planned)  
- Console-based UI (Java)  
- Planned: GUI with JavaFX  

---

## 📦 Project Structure (planned)
myhealth/
├── src/main/java/com/romankafi/myhealth   # Core application  
├── src/test/java/com/romankafi/myhealth   # Unit tests  
├── db/                                    # SQL schema (future)  
├── pom.xml                                # Maven build file  
└── README.md  

---

## 🔧 Setup & Run

Clone repository:
```bash
git clone https://github.com/RomanKAFI/myhealth.git
cd myhealth
Build with Maven:


mvn clean install
Run locally:


mvn exec:java
✅ Roadmap
Initialize project with README, license, gitignore

Implement core classes: Patient, Appointment, Treatment

Add persistence with SQL

Build simple CLI interface

Add JavaFX UI

Expand with REST API

📜 License
MIT License — free to use and modify.
