# 🏨 Hotel Management System

A modern **Hotel Management System** built with **Java** and **Spring Boot** to streamline hotel operations, including room management, reservations, guest administration, and booking workflows. The project follows RESTful API principles and Clean Architecture to ensure scalability, maintainability, and security.

---

## 🚀 Features

- 👤 Guest Management
- 🛏️ Room Management
- 📅 Reservation & Booking System
- 💳 Booking Status Management
- 🔐 JWT Authentication & Authorization
- 👨‍💼 Role-Based Access Control (Admin/User)
- 📊 Dashboard Statistics
- 🔍 Search & Filter Reservations
- 📝 Validation & Exception Handling
- 📄 Swagger API Documentation
- 🗄️ MySQL Database Integration

---

## 🛠️ Tech Stack

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA (Hibernate)
- MySQL
- Maven
- JWT Authentication
- Lombok
- Swagger / OpenAPI
- Docker
- JUnit 5
- GitHub Actions

---

## 📂 Project Structure

```
hotel-management-system
│
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── controller
│   │   │   ├── service
│   │   │   ├── repository
│   │   │   ├── model
│   │   │   ├── dto
│   │   │   ├── security
│   │   │   ├── exception
│   │   │   └── config
│   │   └── resources
│   │       ├── application.properties
│   │       └── data.sql
│   └── test
│
├── Dockerfile
├── pom.xml
└── README.md
```

---

## 📌 API Modules

### Authentication

- Register
- Login
- Refresh Token

### Guests

- Create Guest
- Update Guest
- Delete Guest
- Get Guest Details

### Rooms

- Add Room
- Update Room
- Delete Room
- List Available Rooms

### Reservations

- Create Reservation
- Update Reservation
- Cancel Reservation
- Check-In
- Check-Out
- Booking History

---

## 🔒 Security

- JWT Authentication
- BCrypt Password Encryption
- Role-Based Authorization
- Secure REST Endpoints
- Input Validation
- Global Exception Handling

---

## 🐳 Running with Docker

```bash
docker-compose up --build
```

---

## ▶️ Run Locally

Clone the repository

```bash
git clone https://github.com/yourusername/hotel-management-system.git
```

Navigate to the project

```bash
cd hotel-management-system
```

Build the project

```bash
mvn clean install
```

Run the application

```bash
mvn spring-boot:run
```

---

## 📖 API Documentation

After starting the application, open:

```
http://localhost:8080/swagger-ui/index.html
```

---

## 📊 Future Improvements

- Online Payments
- Email Notifications
- QR Code Check-In
- Room Service Module
- Customer Reviews
- Multi-Hotel Support
- Reporting Dashboard
- AI-Based Room Recommendations

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed as a portfolio project showcasing Java backend development, REST APIs, Spring Boot, authentication, database design, and software architecture best practices.
