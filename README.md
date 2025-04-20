Overview:
Ayushman Bharat is one of India’s largest healthcare schemes, but it is also prone to fraudulent activities such as misuse of beneficiary data and impersonation. Our project, Kalyan Mantra, is an IoT-based fraud detection system that verifies patient identity and logs treatment activities in real time using RFID and cloud-based monitoring.

Objectives:
Detect unauthorized use of Ayushman Bharat cards.

Provide real-time verification using RFID tags.

Log every patient interaction securely in a centralized database.

Alert the authorities or hospital staff in case of suspicious activity.

Tech Stack:
Microcontroller: NodeMCU (ESP8266)

RFID Module: RC522

Cloud Platform: XAMPP (for local MySQL + PHP backend)

Programming Languages: C++ (Arduino), Python, PHP

UI/UX: Android Interface for live updates and alerts

Database: MySQL

Web Server: Apache (XAMPP)

Tools Used: Arduino IDE, Firebase (optional), Django (for dashboard), Figma (for UI design)

Working Principle:
Each patient is assigned an RFID tag linked to their Ayushman card.

When a patient visits a hospital, the RFID is scanned via NodeMCU.

NodeMCU sends the data to the XAMPP server using HTTP.

The backend checks the database to verify card ownership.

If mismatched data or repeated usage is detected, an alert is triggered.

Authorized access is recorded with timestamp and hospital ID.
Key Features:
Real-time fraud detection

Centralized record of patient visits

Compatible with existing hospital workflows

Notifications via app/web interface

Offline logging when Wi-Fi is down (optional)

Impact:
Reduces fraudulent claims in Ayushman Bharat Scheme

Ensures that only legitimate beneficiaries get treatment

Helps hospitals maintain clean audit records

Enables government agencies to track misuse patterns

Learning Outcomes:
Gained practical experience with RFID technology and NodeMCU.

Developed backend services using PHP, MySQL, and XAMPP.

Learned how to connect hardware with software via HTTP.

Built a real-time alerting system and mobile-friendly dashboard.

Understood the importance of secure data flow in healthcare IoT.
