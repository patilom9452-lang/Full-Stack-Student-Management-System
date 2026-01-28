# Full Stack Student Management System

A full stack **Student Management System** built using **React (Vite)** for the frontend, **Spring Boot** for the backend, and **MySQL (XAMPP)** as the database.  
The application allows users to add and view student records using RESTful APIs.

---

## 🚀 Tech Stack

### Frontend
- React.js
- Vite
- JavaScript (ES6+)
- HTML5
- CSS3
- Axios

### Backend
- Java
- Spring Boot
- Spring Data JPA
- REST APIs

### Database
- MySQL (XAMPP)

---

## 📁 Project Structure
fullstack-student-management-system  
│
├── studentFrontend # React + Vite frontend    
│ ├── src  
│ ├── public  
│ ├── index.html  
│ ├── package.json  
│ └── vite.config.js  
│
├── studentSystemBackend # Spring Boot backend  
│ ├── src  
│ ├── pom.xml  
│ ├── mvnw  
│ └── mvnw.cmd  
│
├── .gitignore  
└── README.md

## ⚙️ Setup & Installation

### 1️⃣ Backend Setup (Spring Boot)

1. Open **XAMPP** and start **MySQL**
2. Create a database:
   ```sql
   CREATE DATABASE student_db;
3. Update application.properties:

    spring.datasource.url=jdbc:mysql://localhost:3306/student_db  
    spring.datasource.username=root  
    spring.datasource.password=  
    spring.jpa.hibernate.ddl-auto=update  
    spring.jpa.show-sql=true  

4. Run the backend:

    mvn spring-boot:run
    Backend will run on:
    http://localhost:8080

2️⃣ Frontend Setup (React + Vite)
cd studentFrontend
npm install
npm run dev

Frontend will run on:

http://localhost:5173

🔗 API Endpoints  
Method	Endpoint	Description  
GET	/students	Fetch all students  
POST	/students	Add a new student  

✨ Features

Add student details

View student list

RESTful API integration

Clean frontend-backend separation

MySQL database integration

---
👨‍💻 Author
Om Krishna Hankare
B.E. Computer Science (AI & ML)
Full Stack Developer (React + Spring Boot)


   
