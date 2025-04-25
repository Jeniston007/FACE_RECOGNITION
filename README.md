#Project Explanation
##The project, Efficient Attendance Tracking Using On-Spot Facial Recognition, is a mobile-based system that automates student attendance using real-time facial recognition. It addresses common issues in traditional attendance systems such as manual errors, proxy attendance, and inefficiency. By leveraging on-spot image capturing, transfer learning, and Firebase, the system ensures:

Accurate and secure attendance marking
Real-time verification
Online and offline functionality
Instant notifications and reporting
Scalable deployment for educational institutions
It is designed to provide a modern, touchless solution for daily attendance tracking, replacing outdated roll calls or biometric systems.

Team Members
Team Lead: Thanusri MV (24MCR115)
Team Members:
Nandhaprabhu R (24MCR072)
Selva Sahayam Jeniston S (24MCR096)
Team Mentor:
Mr. S. Hemalatha
Assistant Professor, Department of MCA, Kongu Engineering College
Usage Instructions
Registration:
Students' facial images are initially captured and stored for model training using a small dataset.
Training the Model:
Transfer learning is applied using pre-trained models.
A few sample images per student are used for facial feature learning.
Taking Attendance:
Use a smartphone to capture an image of the entire class.
The image is processed locally using FastAPI server and matched against the trained dataset.
Verification & Status:
Students recognized by the model are marked present.
Attendance status and reports are updated in Firebase.
Reports & Profiles:
Students and teachers can access detailed reports and individual profiles.
System sends real-time notifications if needed.
Pages/Modules:
Home Page – For initial access
Status Page – Shows current attendance status
Recognized Page – Displays students identified in the captured image
