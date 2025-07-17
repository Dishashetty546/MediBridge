# 🏥 MediBridge — Patient Record & Clinic Management System

![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Tech](https://img.shields.io/badge/Stack-MERN-blue)

**MediBridge** is a full-stack web application designed to modernize patient record handling in clinics. It bridges the gap between doctors, patients, and receptionists through a centralized, easy-to-use digital platform.

---

## ❗ Problem Statement

Traditional patient recordkeeping in clinics often leads to:

- Long wait times for registration and checkups
- Misplaced or inaccessible patient history
- Inefficient coordination between doctors and receptionists
- No quick way to retrieve records using phone number or token

> 🔍 There is a need for a lightweight, secure, and digitized platform to streamline patient registration, medical history access, and billing operations in real-time.

---

## 🎯 Key Use Cases

This application is ideal for small to mid-sized clinics. It enables:

- 🧾 Patient registration with **auto-generated token IDs**
- 🩺 Doctors to access real-time medical history and prescriptions
- 💰 Receptionists to manage billing and invoices efficiently
- 🔍 Patient retrieval via **phone number or token ID**
- 🧑‍⚕️ Multiple roles: Receptionist, Doctor, and Admin

---

## 💻 Tech Stack

| Category      | Technology     | Description                             |
| ------------- | -------------- | --------------------------------------- |
| **Frontend**  | React.js       | Interactive user interfaces             |
|               | Axios          | API communication                       |
|               | React Router   | Client-side routing                     |
|               | Tailwind CSS   | Fast, responsive, utility-first styling |
| **Backend**   | Node.js        | Runtime environment                     |
|               | Express.js     | Web server framework                    |
|               | MongoDB        | NoSQL database for patient data         |
|               | Mongoose       | MongoDB object modeling (ODM)           |
|               | JSON Web Token | Role-based authentication & security    |
|               | bcryptjs       | Password hashing                        |
| **Dev Tools** | Nodemon        | Auto-restarts server on changes         |
|               | dotenv         | Manage environment variables            |
| **Database**  | MongoDB Atlas  | Cloud-based database                    |

---

## 📸 Screenshots

| Reception Dashboard                       | Patient Profile                       | Doctor Dashboard                    |
| ----------------------------------------- | ------------------------------------- | ----------------------------------- |
| ![reception](./Screenshots/reception.png) | ![patient](./Screenshots/patient.png) | ![doctor](./Screenshots/doctor.png) |

> 🔎 Add more screenshots or demo GIFs for better presentation.

---

## ⚙️ Setup Instructions

### 🔧 Prerequisites

- Node.js & npm installed
- MongoDB or MongoDB Atlas account
- Git

### 📥 Installation

```bash
# Clone the repository
git clone https://github.com/Dishashetty546/MediBridge.git
cd MediBridge
```
