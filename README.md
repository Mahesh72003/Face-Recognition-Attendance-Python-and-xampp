**Face Recognition Attendance System**
This project implements a face recognition-based attendance system using Python, OpenCV, and XAMPP. The system captures images of students and teachers, processes them, and marks attendance by recognizing faces in real-time. It stores attendance records in a MySQL database through a web interface built with HTML, CSS, JS, PHP, and SQL.

**Features**
1. Face Recognition: Detects and recognizes faces using OpenCV and the face_recognition library.
2. Real-Time Attendance: Marks attendance in real-time through a web interface.
3. Multiple Camera Integration: Uses a laptop camera for student attendance and a USB camera for teacher attendance.
4. Database Management: Stores attendance records in a MySQL database using XAMPP.
5. Automated Notifications: Sends WhatsApp messages and Telegram bot notifications when attendance is marked.
6. Web Interface: A user-friendly web interface to view attendance records.
**Technologies Used
Backend:**
1. Python: Core logic for face recognition and attendance marking.
2. OpenCV: For image and video processing.
3. Face_Recognition: For face detection and recognition.
5. MySQL: Database to store attendance records.
6. PHP: Server-side logic for handling database operations.
**Frontend:**
1. HTML/CSS/JavaScript: To create a responsive and interactive user interface.
2. XAMPP: Provides the Apache web server and MySQL for database management.
**Hardware:**
1. Laptop Camera: Used to capture images for face recognition (for students).
2. USB Camera: Captures images for teacher attendance.

**Installation**
Prerequisites:
Python
XAMPP (Apache, MySQL)

**Step-by-Step Setup:**
1. Clone the Repository:
  git clone https://github.com/Mahesh72003/Face-Recognition-Attendance-Python-and-xampp
  cd Face-Recognition-Attendance-Python-and-xampp
2. Install Python Dependencies:
  pip install -r requirements.txt
3. Set Up XAMPP:
  Start Apache and MySQL services in XAMPP.
  Import the attendance_db.sql file to create the required database and tables.
4. Run the Face Recognition Script:
5. Access the Web Interface:
  Navigate to http://localhost/Face-Recognition-Attendance-Python-and-xampp/Web/index.html to view attendance records and manage the system.

**Usage**
1. Use the camera to capture images of students and teachers.
2. Run the face recognition system to identify individuals and mark attendance.
3. View attendance records via the web interface.
4. Automatically send notifications through WhatsApp and Telegram upon successful attendance marking.
5. Future Enhancements
6. Add an admin dashboard to manage users and view detailed attendance analytics.
7. Improve face recognition accuracy with additional training data.

**Contributions**
Contributions are welcome! Feel free to fork the repository and submit pull requests.
