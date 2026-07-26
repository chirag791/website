# Chirag Saini – Developer Portfolio

A personal portfolio website showcasing my skills, projects, and background as a Backend & DevOps Engineer. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies.

🌐 **Live Site:** [chiragcv.com](https://chiragcv.com)

---

## 👤 About Me

- **Name:** Chirag Saini
- **Degree:** B.Tech CSE (AI & ML) – Panipat Institute of Engineering and Technology (2024–2028)
- **Location:** Panipat, Haryana, India
- **Email:** chiragsaini1607@gmail.com
- **Phone:** +91 8295972122
- **GitHub:** [github.com/chirag791](https://github.com/chirag791)
- **LinkedIn:** [chirag-s-b6148b372](https://www.linkedin.com/in/chirag-s-b6148b372)

---

## 📁 Project Structure

```
portfolio/
├── index.html       # Main HTML – all sections (Hero, About, Skills, Projects, Education, Contact)
├── styles.css       # All styling – dark/light theme, animations, responsive layout
├── script.js        # JS – particles, tilt effect, scroll animations, theme toggle, contact form
├── profile.jpg      # Profile photo used in Hero and About sections
├── CNAME            # Custom domain config → chiragcv.com
└── README.md        # This file
```

---

## 🚀 Featured Projects

### 1. Payment Service Microservice *(Enterprise-Level)*
- Full-featured RESTful API with credit card management, OTP verification, fraud detection, refunds, and transaction history
- **Stack:** Java 21, Spring Boot 3.1, MongoDB, Docker, Kubernetes, Jenkins, SonarQube, Maven
- CI/CD pipeline: Jenkins (build → test → Docker image → K8s deploy)
- Swagger UI + Spring Actuator + Javadoc documentation

### 2. Payment Service CI/CD – GitHub Actions & AWS EC2 *(Cloud DevOps)*
- Extended the Payment Service with a GitHub Actions-based cloud deployment pipeline
- Workflow: Spring Boot build → Docker image → Docker Hub push → AWS EC2 SSH deploy
- **Stack:** Java 21, Spring Boot, Docker, GitHub Actions, AWS EC2

### 3. User Microservice – Python REST API *(Python Microservice)*
- Lightweight user management service with full CRUD, Pydantic validation, and auto-generated Swagger docs
- **Stack:** Python, FastAPI, Pydantic, Uvicorn, Docker

### 4. Credit Card Application *(Spring Boot)*
- Credit card management app with RESTful API design and MongoDB integration
- **Stack:** Java, Spring Boot, Spring Data MongoDB, Maven

---

## 🛠️ Tech Stack

| Category       | Technologies                                              |
|----------------|-----------------------------------------------------------|
| Languages      | Java 21, Python                                           |
| Frameworks     | Spring Boot 3.x, FastAPI, Spring Data MongoDB, Pydantic   |
| Databases      | MongoDB                                                   |
| DevOps / CI-CD | Docker, Kubernetes, Jenkins, GitHub Actions, SonarQube    |
| Cloud          | AWS EC2                                                   |
| Tools          | Maven, Gradle, Swagger/OpenAPI, Postman, Git, Javadoc     |

---

## ✨ Website Features

- **Dark / Light theme toggle** with localStorage persistence
- **Floating particle canvas** with connecting lines (vanilla JS Canvas API)
- **3D card tilt effect** on project and skill cards (mousemove)
- **Scroll-triggered fade-in animations** via IntersectionObserver
- **Scroll progress bar** at the top of the page
- **Active nav link highlighting** based on scroll position
- **Responsive design** with hamburger menu for mobile
- **Contact form** that opens the user's email client via `mailto:`
- **Back to top** button

---

## 🏃 Running Locally

No build step required. Just open the file directly:

```bash
# Clone or download the repo, then:
open index.html
# or on Windows:
start index.html
```

Or serve it with a simple local server:

```bash
npx serve .
# or
python -m http.server 8080
```

---

## 🌐 Deployment

This site is deployed via **GitHub Pages** with a custom domain.

- Custom domain configured in `CNAME` → `chiragcv.com`
- Any push to the main branch auto-deploys via GitHub Pages

---

## 📬 Contact

Feel free to reach out for internship opportunities, collaborations, or just a chat about backend development and DevOps!

- 📧 [chiragsaini1607@gmail.com](mailto:chiragsaini1607@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/chirag-s-b6148b372)
- 🐙 [GitHub](https://github.com/chirag791)

---

*Designed & Built by Chirag Saini · 2025*
