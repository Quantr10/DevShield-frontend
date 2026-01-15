# DevShield (Frontend)

React Single-Page Application (SPA) for the DevShield secure banking platform.  
Provides a responsive UI with protected routes and real-time transaction feedback.

> Backend Repository → https://github.com/Quantr10/DevShield-backend

---

## 🛠 Tech Stack

**Frontend:** React, JavaScript, HTML, CSS  
**Backend:** Spring Boot, Spring Security, JWT, REST APIs  
**Database:** MySQL  
**DevOps:** Docker, GitHub Actions  
**Cloud:** AWS S3  
**Tools:** Git, Maven, npm 

---

## ✨ Features

- Secure Deposit, Withdrawal, and Transfer APIs  
- JWT Authentication & Role-based Authorization  
- ACID-compliant transaction handling & audit logging  
- React SPA with protected routes & real-time feedback  
- SMTP email notifications (password reset, transaction alerts)  
- Dockerized full-stack app with GitHub Actions CI/CD  
- AWS S3 integration & cloud-ready deployment  

---

## ⚙️ Getting Started
### Clone Repository

```
git clone https://github.com/quantr10/devshield-frontend.git
cd devshield-frontend
```
### Environment Setup

Copy the example environment file:

```bash
cp .env.example .env
```

### Run with Docker
```
docker-compose up --build
```
Frontend runs at: http://localhost:3000

### Run without Docker
```
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
