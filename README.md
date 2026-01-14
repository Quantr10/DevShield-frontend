# DevShield

DevShield is a **secure full-stack banking platform** featuring real financial transaction flows, enterprise-grade security, and automated deployment pipelines.

Built with **Spring Boot**, **React**, **MySQL**, and **Docker**, DevShield demonstrates secure financial APIs, authentication & authorization, CI/CD automation, and cloud deployment — mirroring real-world fintech systems.

---

## ✨ Features

### Core Banking
- Deposit, Withdrawal, and Transfer APIs  
- ACID-compliant transaction handling  
- Customer & Auditor role separation  
- Full audit logging of all actions  

### Security
- Spring Security authentication  
- JWT-based stateless authorization  
- Password encryption with BCrypt  
- Protected API routes  

### Frontend
- React Single-Page Application (SPA)  
- JWT-protected pages  
- Responsive UI  
- Real-time transaction feedback  

### Notifications
- SMTP email service  
- Password reset emails  
- Transaction confirmation alerts  

### DevOps & Cloud
- Dockerized frontend & backend  
- GitHub Actions CI/CD  
- Automated build & test pipeline  
- AWS S3 file storage integration  
- Ready for zero-downtime deployment  

---

## 🛠 Tech Stack

**Frontend:** React, JavaScript, HTML, CSS  
**Backend:** Spring Boot, Spring Security, JWT, REST APIs  
**Database:** MySQL  
**DevOps:** Docker, GitHub Actions  
**Cloud:** AWS S3  
**Tools:** Git, Maven, npm  

---

## ⚙️ Getting Started

### Clone Repository

```bash
git clone https://github.com/quantr10/DevShield.git
cd DevShield
```

### Environment Setup
Copy the example environment file:

```
cp .env.example .env
```
Fill in required credentials in .env.

### Run with Docker
```
docker-compose up --build
```
Access the application:
#### Frontend: http://localhost:3000
#### Backend: http://localhost:8080

### Run without Docker
#### Backend
```
cd backend
mvn spring-boot:run
```

#### Frontend
```
cd frontend
npm install
npm start
```

## 🔄 CI/CD Pipeline

On every push to main:
- Runs backend tests
- Builds frontend
- Builds Docker images
- Ready for automated cloud deployment

Configured in:

```
.github/workflows/deploy.yml
```

## ☁️ Cloud Integration

- AWS S3 for secure file storage
- Container-ready for AWS EC2 / ECS / Render / Railway
- CI/CD prepared for zero-downtime deployment

## 📸 Demo
(Add screenshots or GIFs here)

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)

