# Campus Lost & Found Java Web Application

A centralized, secure, and user-friendly web application designed to streamline the lost and found process on a college campus. Built using Java Servlets, JSP, and MySQL.

📌 Project Overview

In a busy college environment, losing personal belongings like ID cards, wallets, or electronics is a common stress. The traditional manual system of logbooks and decentralized offices is inefficient and insecure.

Campus Lost & Found solves this by providing a single online platform where:

Students & Staff can report lost items and search for found items 24/7.

Finders can easily post items they have found.

Administrators can manage claims and verify ownership securely.

The core innovation of this project is the "Secret Question" verification system, which ensures items are returned only to their rightful owners.

🚀 Features

User Authentication: Secure registration and login for students, staff, and admins.

Report Lost/Found Items: Intuitive forms to post details about lost or found belongings.

Smart Search: Filter found items by category or keyword to quickly find matches.

Secure Claim Process: Claimants must answer a secret question set by the original owner to prove ownership.

User Dashboard: personalized view to track the status of your reported items and claims.

Admin Dashboard: A powerful interface for administrators to review claims, compare verification answers, and approve/reject requests.

🛠️ Tech Stack

Frontend: HTML5, CSS3, JSP (JavaServer Pages), JSTL

Backend: Java Servlets, JDBC (Java Database Connectivity)

Database: MySQL 8.0

Server: Apache Tomcat 9.0

Build Tool: Apache Maven

IDE: Visual Studio Code / Eclipse

📸 Screenshots

(Add your screenshots here. You can drag and drop images into your GitHub repo or use an image hosting link)

Login Page
![login](https://github.com/user-attachments/assets/c7fd3459-afb8-4e08-a0e6-aac10802e006)

User Dashboard

![user dashboard](https://github.com/user-attachments/assets/a6926b21-e452-4017-857c-899ab0ae2a54)
Reporting item

![Reprting Item](https://github.com/user-attachments/assets/cd16bc78-d4e6-4008-8f8e-951a57786620)


Search Results
![Searching](https://github.com/user-attachments/assets/a59afe0d-3206-470a-9e92-0f06cabf061f)







⚙️ Setup & Installation

Follow these steps to run the project locally:

Prerequisites:

Java Development Kit (JDK) 8 or higher

Apache Tomcat Server 9.0

MySQL Server

A Java IDE (like VS Code or Eclipse)

Steps:

Clone the Repository:

git clone [https://github.com/your-username/campus-lost-and-found.git](https://github.com/your-username/campus-lost-and-found.git)


Setup Database:

Open MySQL Workbench (or any SQL client).

Run the script located in database/database_setup.sql to create the database and tables.

Note: Update the database credentials in src/com/example/util/DatabaseConnection.java if your MySQL password is different.

Import Project:

Open your IDE and import the project as a "Maven Project".

Run on Server:

Right-click the project -> Run As -> Run on Server.

Select your Tomcat server instance.

Access the App:

Open your browser and go to: http://localhost:8080/LostAndFoundApp/

📂 Project Structure

LostAndFoundApp/
├── src/
│   ├── main/
│   │   ├── java/com/example/
│   │   │   ├── dao/          
│   │   │   ├── model/       
│   │   │   ├── servlet/     
│   │   │   └── db/         
│   │   └── webapp/
│   │       ├── WEB-INF/     
│   │       ├── css/        
│   │       ├── js/         
│   │       ├── *.jsp         
├── target/                  
└── pom.xml                  



Developed by: Fouzan & Team
College: AWH ENGINEERING COLLEGE CALICUT
