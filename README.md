TODO

### 🔹 Backend

* Java 17+
* Spring Boot
* Spring Data JPA
* H2 In-Memory Database
* Maven
* Runs on: **[http://localhost:8081](http://localhost:8081)**

### 🔹 Frontend

* React
* Axios
* Node.js & npm
* Runs on: **[http://localhost:3000](http://localhost:3000)**

---

## ✨ Features

* ➕ Add new todos
* 📋 View all todos
* ✅ Mark todos as complete / incomplete
* 🗑️ Delete todos
* 🔄 Real-time UI updates
* 💾 In-memory H2 database (no setup required)

---

## 🏗️ Application Architecture

```
React (Frontend - Port 3000)
        ↓ REST API (Axios)
Spring Boot (Backend - Port 8081)
        ↓
H2 Database (In-Memory)
```

---

## 📂 Project Structure

```
todo-app/
│
├── todo-backend/
│   ├── controller/
│   ├── model/
│   ├── repository/
│   ├── TodoApplication.java
│   └── application.properties
│
└── todo-frontend/
    ├── src/
    │   ├── App.js
    │   └── index.js
    └── package.json
```

---

## ▶️ How to Run the Project Locally

### ✅ Prerequisites

* Java 17 or above
* Node.js & npm
* Maven

---

### 🔹 Backend Setup (Spring Boot)

```bash
cd todo-backend
mvn clean install
mvn spring-boot:run
```

Backend will start at:
👉 **[http://localhost:8081](http://localhost:8081)**

H2 Console (optional):
👉 **[http://localhost:8081/h2-console](http://localhost:8081/h2-console)**

---

### 🔹 Frontend Setup (React)

```bash
cd todo-frontend
npm install
npm start
```

Frontend will start at:
👉 **[http://localhost:3000](http://localhost:3000)**

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint    | Description        |
| ------ | ----------- | ------------------ |
| GET    | /todos      | Get all todos      |
| POST   | /todos      | Add new todo       |
| PUT    | /todos/{id} | Update todo status |
| DELETE | /todos/{id} | Delete todo        |

---
d
* Deployment using Docker / Cloud

