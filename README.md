
# 🏥 SRS-for-Hajzi-Android-Hospital-Appointment-App

## 📌 Overview

**Hajzi** is an Android-based hospital reservation system designed to simplify the appointment process for patients while helping hospitals efficiently manage reservations. It allows patients to register, book, cancel, and reschedule appointments — all through a user-friendly mobile application.

---

## 🧭 Project Scope

Hajzi eliminates the need for traditional phone-based or in-person booking by digitizing the entire process. It offers a more efficient, accurate, and accessible way to manage hospital appointments with minimal administrative overhead.

---

## 🎯 Key Features

- **Sign-Up & Login**: Secure registration and authentication using ID or email and password.
- **Search Clinics & Doctors**: View available clinics, times, and doctors.
- **Manage Reservations**: Schedule, view, and cancel appointments with real-time validation.
- **Notifications**: SMS and email alerts to confirm or remind users about appointments.
- **Multi-role Access**:
  - 👤 Patients: Manage appointments, view history, rate services.
  - 🩺 Doctors: Handle schedules, absences, vacations.
  - 🛠️ Admin: Generate reports and manage reservation data.

---

## 💻 Technical Stack

| Layer              | Technology              |
|-------------------|--------------------------|
| Platform          | Android (Java)           |
| IDE               | Android Studio           |
| Database          | NoSQL                    |
| Notification APIs | SMS & Email integration  |

---

## 📱 User Interfaces

- **Patients**: Sign up, search clinics, view and manage appointments.
- **Doctors**: Profile view, schedule control, salary & absence tracking.
- **Admins**: Access to logs, statistics, and user activity.

UI validation includes:
- Strong password requirements
- No numbers in name fields
- Real-time input error feedback

---

## 🔐 Non-Functional Requirements

- **Performance**: < 2 seconds response time for any operation.
- **Scalability**: Supports up to 20,000 concurrent users.
- **Security**:
  - Role-Based Access Control
  - Encrypted user data
  - Secure logging & auditing
- **Usability & Accessibility**: 24/7 availability with intuitive navigation.
- **Maintainability & Testability**: Modular and test-ready design.

---

## 📊 Business Rules

- Only registered users can book appointments.
- Cancellations are allowed up to 48 hours in advance.
- Users must be online to interact with the system.

---

## 📂 Documentation

- **Installation Guide** (for Android 8+ devices)
- **User Manuals**: Tailored for Patients, Doctors, and Admins.
- **Video Tutorials**: Step-by-step demos for app usage.

---

## 👥 Team Members

- Eyad Maccawy  
- Enad Alharbi *(Team Leader)*  
- Turki Alotaibi  
- Jawad Alotaibi  
