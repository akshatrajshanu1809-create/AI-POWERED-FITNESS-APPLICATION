# AI-Powered Fitness Application

An AI-powered fitness application built using a microservices architecture with Spring Boot. The application helps users manage their fitness journey by providing workout recommendations, tracking progress, and securely managing user data.

---

## Features

- User authentication and authorization
- Personalized workout recommendations
- Exercise and fitness plan management
- RESTful APIs for communication between services
- API Gateway for request routing
- Service discovery using Eureka Server
- Secure backend using Spring Boot
- Responsive frontend built with HTML, CSS, and JavaScript
- MySQL database integration

---

## Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot
- Spring Cloud Gateway
- Spring Cloud Eureka
- REST APIs

### Database
- MySQL

### Tools
- Git
- GitHub
- Maven
- IntelliJ IDEA

---

## Architecture

The project follows a microservices architecture where each service performs a specific responsibility.

Main Components:

- API Gateway
- Eureka Service Registry
- Authentication Service
- Fitness Service
- User Service
- Database

---

## Project Structure

```
fitness-application/
│
├── api-gateway
├── eureka-server
├── authentication-service
├── fitness-service
├── user-service
├── frontend
└── README.md
```

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/fitness-application.git
```

### Navigate to the Project

```bash
cd fitness-application
```

### Start Eureka Server

```bash
mvn spring-boot:run
```

### Start API Gateway

```bash
mvn spring-boot:run
```

### Start All Microservices

Run each Spring Boot service individually.

### Launch Frontend

Open the frontend in your browser or serve it using any local web server.

---

## Future Improvements

- AI chatbot for fitness guidance
- Diet recommendation system
- BMI and calorie calculator
- Workout history tracking
- Email notifications
- Mobile application support
- Docker and Kubernetes deployment

---

## Learning Outcomes

This project helped in understanding:

- Spring Boot development
- Microservices architecture
- REST API development
- API Gateway
- Eureka Service Discovery
- MySQL integration
- Frontend and backend communication
- Git and GitHub workflow

---

## Screenshots

Add screenshots of the application here.

---

## Author

**Akshat Raj**

GitHub: https://github.com/akshatrajshanu1809-create

---

## License

This project is created for learning and educational purposes.
