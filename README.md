🎓 Student Wellness System

A Java Swing desktop application that manages student wellness through counselor appointments, feedback submission, and administrative oversight.

📌 Project Overview

The Student Wellness System is designed to streamline the process of managing student counseling services. It allows students to book appointments, view counselor availability, and provide feedback. Administrators can manage counselors, update bookings, and track feedback — all within a clean, user-friendly GUI.

✅ Features

🗕️ Book, update, cancel, and view counseling appointments

👩‍🏫 Add, update, and delete counselor records

📝 Submit and review student feedback

📋 Appointment validation (no double bookings, no past dates)

🎨 Color-coded appointment status (Scheduled, Completed, Cancelled)

🔁 Real-time dropdown updates for available counselors

🩵 Follows the MVC (Model-View-Controller) architecture

🛠️ Technologies Used

Java SE
Swing GUI Toolkit
JDBC (Java Database Connectivity)
Embedded JavaDB (Derby)
NetBeans / IntelliJ IDEA for development

📂 Project Structure
``` bash
├── gui/               # GUI components (Views)
│   ├── MainApp.java
│   ├── AppointmentsPanel.java
│   ├── CounselorsPanel.java
│   └── FeedbackPanel.java
│
├── dao/               # Data Access Layer
│   ├── AppointmentDAO.java
│   ├── CounselorDAO.java
│   ├── FeedbackDAO.java
│   └── DatabaseConnection.java
│
├── model/             # POJOs (Model)
│   ├── Appointment.java
│   ├── Counselor.java
│   └── Feedback.java
│
├── resources/         # Images/icons and data
└── README.md
```
🚦 Usage Instructions

Clone the repo
git clone https://github.com/your-username/student-wellness-system.git
Open the project in NetBeans or IntelliJ.
Run MainApp.java to launch the application.
Database tables will be auto-created on first launch.

📌 Notes

Ensure JavaDB (Derby) is configured properly in your environment.
All appointment times are hardcoded in AppointmentsPanel.java but can be modified as needed.
Data is persisted using embedded SQL tables managed via JDBC.

👩‍💻 Author

Tatyana Hlamulo
Bachelor of Computing – Software Engineering
Belgium Campus ITversity
