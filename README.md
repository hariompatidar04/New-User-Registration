# New-User-Registration
# 📝 Spring Boot User Registration App


Uploading Screen Recording 2025-04-17 133034.mp4…
  
It demonstrates how to implement:

- ✅ New User Registration
- 🔐 Password Encryption with Spring Security
- ⚖️ Backend Validation using Jakarta Bean Validation (Hibernate Validator)
- 📂 Persistence using Spring Data JPA
- 🗃️ H2 In-Memory Database (for development/testing)

---

## 🚀 Features

- Register new users with `username` and `password`
- Validate input fields (e.g., password length,username length)
- Store users securely with encrypted passwords
- Prevent duplicate username
- In-memory database viewable via H2 console

---

# Tech Stack

| Technology         | Purpose                         |
|--------------------|---------------------------------|
| Spring Boot        | Main application framework      |
| Spring Security    | Password encoding + auth        |
| Spring Data JPA    | ORM and repository layer        |
| Hibernate Validator| Input validation                |
| H2 Database        | In-memory development database  |

---

## 🧪 API Endpoints

| Method | Endpoint       | Description             |
|--------|----------------|-------------------------|
| POST   | `/api/auth/signup` | Register a new user     |

Sample JSON:
```json
{
  "username": "om",
  "password": "secure123"
}
