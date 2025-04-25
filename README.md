# Efficient Attendance Tracking Using On-Spot Facial Recognition

## 📌 Project Overview

The project, Efficient Attendance Tracking Using On-Spot Facial Recognition, is a mobile-based system that automates student attendance using real-time facial recognition. It addresses common issues in traditional attendance systems such as manual errors, proxy attendance, and inefficiency. By leveraging on-spot image capturing, transfer learning, and Firebase, the system ensures:

- Accurate and secure attendance marking
- Real-time verification
- Online and offline functionality
- Instant notifications and reporting
- Scalable deployment for educational institutions
It is designed to provide a modern, touchless solution for daily attendance tracking, replacing outdated roll calls or biometric systems.

---

## 👥 Team Members

| Name                    | Role         | Roll Number   |
|-------------------------|--------------|---------------|
| Thanusri MV             | Team Lead    | 24MCR115      |
| Nandhaprabhu R          | Member       | 24MCR072      |
| Selva Sahayam Jeniston S| Member       | 24MCR096      |

**Mentor:**  
- Mr. S. Hemalatha  
  Assistant Professor, MCA Department, Kongu Engineering College

---

## 🚀 Technology Stack

- **Frontend**: Flutter (or Android App)
- **Backend**: FastAPI
- **Database**: Firebase
- **ML Model**: Transfer Learning for Face Recognition

---

## 🧠 Modules

- **Registration** – Register student faces for training  
- **Camera** – Capture class images for attendance  
- **Attendance Status** – Shows present/absent status  
- **Attendance Report** – Maintains historical records  
- **Profile** – Student-specific info

---

## 🔁 Usage Instructions

### 1. Registration:
- Students' facial images are initially captured and stored for model training using a small dataset.
### 2. Training the Model:
- Transfer learning is applied using pre-trained models.
- A few sample images per student are used for facial feature learning.
### 3. Taking Attendance:
- Use a smartphone to capture an image of the entire class.
- The image is processed locally using FastAPI server and matched against the trained dataset.
### 4. Verification & Status:
- Students recognized by the model are marked present.
- Attendance status and reports are updated in Firebase.
### 5. Reports & Profiles:
- Students and teachers can access detailed reports and individual profiles.
- System sends real-time notifications if needed.
### 6. Pages/Modules:
- Home Page – For initial access
- Status Page – Shows current attendance status
- Recognized Page – Displays students identified in the captured image
---


