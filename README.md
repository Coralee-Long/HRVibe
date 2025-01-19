# HRVibe - Personalized Health Optimization

HRVibe is a personal full-stack project designed to analyze and visualize health
metrics. It demonstrates modern web development practices by combining a React +
TypeScript frontend with a Spring Boot backend. The project integrates with the
Garmin Connect API to process real-world health data, showcasing the ability to
build data-driven applications.

---

## 1. Overview

HRVibe aims to help users gain insights into their health by analyzing data such
as heart rate variability (HRV), sleep metrics, stress levels, and activity
tracking. The project is designed to optimize personal health management while
serving as a showcase of full-stack development skills.

---

## 2. Features

- Integration with the Garmin Connect API to retrieve health and activity data.
- Visualization of HRV, sleep, and activity metrics using interactive charts.
- Backend powered by Spring Boot with MongoDB for secure and efficient data
  handling.
- Modern frontend built with React, TypeScript, and Vite.
- Fully containerized for easy deployment with Docker.

---

## 3. Tech Stack

#### Frontend:

- React
- TypeScript
- Vite
- ESLint and Prettier for code quality
- [Frontend README](frontend/README_FE)

**Backend:**

- Spring Boot (Java 17)
- MongoDB
- REST APIs
- [Backend README](backend/README_BE.md)

**Tools:**

- Docker for containerization
- IntelliJ IDEA for development
- SonarCloud for code analysis

---

## How to Run

This project is currently under development and designed for personal use. To
set up and run locally:

**Frontend Setup: `http://localhost:3000`**

```bash
  cd frontend
  npm install
  npm run dev
```

**Backend Setup: `http://localhost:8080`**

```bash
  cd backend
  mvn spring-boot:run
```

---

## Future Plans

- Add a guest login with demo data for showcasing the project.
- Deploy the project to a live environment for easy access.
- Implement AI-driven insights for advanced health recommendations.



