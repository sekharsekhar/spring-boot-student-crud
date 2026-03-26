# 🚀 Spring Boot Student CRUD Application

## 📌 Project Overview

This is a simple **Spring Boot CRUD application** that performs basic operations on Student data using **REST APIs** and **MySQL database**.

---

## 🛠️ Tech Stack

* **Backend:** Spring Boot
* **Database:** MySQL
* **ORM:** Spring Data JPA (Hibernate)
* **Build Tool:** Maven
* **Testing Tool:** Postman

---

## 📂 Project Structure

```
com.example.demo
│── controller   # Handles API requests
│── service      # Business logic
│── repository   # Database operations
│── entity       # Database model
```

---

## ⚙️ Features

* ✅ Create Student
* ✅ Get All Students
* ✅ Get Student by ID
* ✅ Delete Student

---

## 🔗 API Endpoints

### ➤ Create Student

* **POST** `/students`

```json
{
  "name": "Sekhar",
  "age": 21,
  "course": "CSE"
}
```

---

### ➤ Get All Students

* **GET** `/students`

---

### ➤ Get Student by ID

* **GET** `/students/{id}`

---

### ➤ Delete Student

* **DELETE** `/students/{id}`

---

## 🗄️ Database Configuration

Update your `application.properties` file:

```
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/spring-boot-student-crud.git
```

2. Open in IntelliJ / Eclipse

3. Start MySQL server and create database:

```sql
CREATE DATABASE student_db;
```

4. Run the application:

```
mvn spring-boot:run
```

---

## 🧪 Testing

Use **Postman** to test APIs:

* POST → Create data
* GET → Fetch data
* DELETE → Remove data

---

## 📸 Future Improvements

* ✏️ Add Update API
* 🔐 Add Validation
* ⚠️ Exception Handling
* 🌐 Connect with React Frontend

---

## 👨‍💻 Author

**Sekhar**
Aspiring Software Engineer 🚀
