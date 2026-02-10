# 🔐 Spring Boot Authentication System

A Spring Boot web application demonstrating user registration, login, and Google OAuth 2.0 authentication using Spring Security.

## 🚀 Features
- User registration and login forms
- Google OAuth 2.0 authentication
- Spring Security for secure auth
- Simple HTML/CSS frontend
- Maven-based project structure
- Beginner-friendly implementation

## 🛠️ Tech Stack
| Category      | Technologies                     |
|---------------|----------------------------------|
| **Backend**   | Java, Spring Boot               |
| **Security**  | Spring Security, OAuth 2.0      |
| **Frontend**  | HTML, CSS                       |
| **Build**     | Maven                           |

## 📂 Project Structure
```
spring-boot-auth/
├── src/
│   └── main/
│       ├── java/           # Spring Boot source code
│       └── resources/      # HTML, CSS, configs
├── pom.xml                # Maven dependencies
├── mvnw / mvnw.cmd        # Maven wrapper
└── README.md              # Documentation
```

## 🔐 Authentication Flow
1. **Form Login**: Register/login with email/password
2. **Google OAuth**: Authenticate via Google account
3. **Spring Security**: Handles auth & authorization
4. **Redirect**: Successful login → secured dashboard

## ⚙️ Setup Instructions

### Prerequisites
- Java 17+
- Maven 3.6+

### Run Project
```bash
# Clone repository
git clone https://github.com/samruddhi2865/Authapp.git
cd spring-boot-auth

# Start application
mvn spring-boot:run
```

**Visit:** `http://localhost:8080`

**Google OAuth Setup:**
1. Create Google OAuth credentials at [Google Cloud Console](https://console.cloud.google.com/)
2. Add `CLIENT_ID` and `CLIENT_SECRET` to `application.properties`

## 🎯 Learning Outcomes
- Spring Boot project structure
- Spring Security authentication
- Google OAuth 2.0 integration
- Frontend-backend connection

## 🔮 Future Enhancements
- Database user persistence
- Role-based access control
- Bootstrap/React UI
- Logout & session management
- JWT token support

## 👩‍💻 Author
**Samruddhi Kshirsagar**  
B.Tech CSE (AIML)
