🚀 Project Overview

This Hospital Management System helps simplify hospital tasks such as:

.Adding new patient details

.Viewing all employees

.Managing rooms & departments

.Updating patient details

.Checking ambulance info

.Searching rooms

.Patient discharge process

.User login & logout

All modules are built using Swing components, and the database connection is handled using JDBC.

🛠️ Tech Stack
1.Frontend (GUI)	Java Swing, AWT
2.Backend	Core Java, JDBC
3.Database	MySQL, MySQL Workbench
4.IDE Used	IntelliJ IDEA
5.Build Tool	No build tool (pure Java project)

Hospital_management_system/
│
├── src/
│   └── hospital.management.system/
│       ├── ALL_Patient_info.java
│       ├── Ambulance.java
│       ├── conn.java
│       ├── Department.java
│       ├── Employee_info.java
│       ├── Login.java
│       ├── NEW_PATIENT.java
│       ├── patient_discharge.java
│       ├── Reception.java
│       ├── Room.java
│       ├── SearchRoom.java
│       └── update_patient_details.java
│
├── icon/                                          
├── screenshots/          
├── README.md
└── .gitignore

⭐ Main Features

✔ Add New Patient
✔ Update Patient Details
✔ Patient Discharge
✔ Room Management
✔ Department List
✔ Employee Info
✔ Ambulance Info
✔ Search Room
✔ Admin Login System
✔ Clean Dashboard with Buttons
✔ Simple & User-Friendly Swing UI

🛢️ Database Structure (MySQL)

Create these tables manually OR import your .sql file if you have one.

Example tables you may be using:

.patient
.employee
.department
.room
.ambulance
.login
Your connection class must match your MySQL credentials.

Example:

String url = "jdbc:mysql://localhost:3306/hospitalmanagement";
String username = "root";
String password = "yourpassword";

▶️ How to Run This Project Locally

1️⃣ Install Required Software
Java JDK 8 or later

.IntelliJ IDEA
.MySQL Server
.MySQL Workbench
.MySQL Connector JAR

2️⃣ Clone the GitHub Repository
git clone https://github.com/Shaikyasmeen1/Hospital_management_system.git

3️⃣ Open in IntelliJ IDEA
Open IntelliJ
Click File → Open
Select your project folder

4️⃣ Add MySQL Connector

1.Download MySQL connector:
2.mysql-connector-j-8.x.x.jar
3.In IntelliJ → File → Project Structure → Libraries
4.Click + Add
5.Add the downloaded JAR

5️⃣ Create Database in MySQL Workbench
Run below query:

CREATE DATABASE hospitalmanagement;
USE hospitalmanagement;
Create your necessary tables.

6️⃣ Update Your Connection File
Open conn.java and update:

String url = "jdbc:mysql://localhost:3306/hospitalmanagement";
String username = "root";
String password = "yourpassword";

7️⃣ Run the Application

Open:
src/hospital.management.system/Login.java

Right-click → Run 'Login.main()'

The login window will appear.

✅ Option 3 — Clean & Professional
## 📌 Real-Time Project Overview
This Hospital Management System simulates real-world operational requirements seen in hospitals and clinics.  
The project demonstrates how core Java, Swing UI, and MySQL can be applied to solve real-time business problems.




