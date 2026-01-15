# DevShield (Frontend)

React Single-Page Application (SPA) for the DevShield secure banking platform.  
Provides a responsive UI with protected routes and real-time transaction feedback.

> Backend Repository → https://github.com/quantr10/DevShield-backend

---

## 🛠 Tech Stack

**Frontend:** React, JavaScript, HTML, CSS  
**Backend:** Spring Boot, Spring Security, JWT, REST APIs  
**Database:** MySQL  
**DevOps:** Docker, GitHub Actions  
**Cloud:** AWS S3  
**Deployment:** AWS EC2  
**Tools:** Git, Maven, npm 

---

## ✨ Features

- JWT-protected authentication flow  
- Secure customer dashboard  
- Deposit, Withdrawal, and Transfer forms  
- Protected routes & role-based UI access  
- Real-time API integration with backend 

---

## ⚙️ Getting Started
### Clone Repository

```bash
git clone https://github.com/quantr10/DevShield-frontend.git
cd devshield-frontend
```
### Environment Setup
Copy the example environment file:

```bash
cp .env.example .env
```
Fill in required credentials in .env.

### Run with Docker
```bash
docker-compose up --build
```
Frontend runs at: http://localhost:3000

### Run without Docker
```
npm install
npm start
```

---
## 📸 Demo
(Add screenshots or GIFs here)

---
## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)
