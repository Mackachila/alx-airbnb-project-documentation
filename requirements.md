# Backend Requirements Specification - ALX Airbnb Clone

This document outlines the technical and functional requirements for three key backend features of the ALX Airbnb Clone system:

- User Authentication
- Property Management
- Booking System

---

## 1. User Authentication

### 🎯 Objective
Enable secure user registration, login, and session handling for guests and hosts.

### 📌 API Endpoints

| Method | Endpoint              | Description                  |
|--------|-----------------------|------------------------------|
| POST   | `/api/auth/register`  | Register a new user account  |
| POST   | `/api/auth/login`     | Authenticate user credentials |
| GET    | `/api/auth/profile`   | Fetch authenticated user info |

---

### 📥 Input Example

**POST /api/auth/register**
```json
{
  "name": "Brian Otieno",
  "email": "brian.otieno@gmail.com",
  "password": "SecurePass2024!",
  "role": "host"
}
