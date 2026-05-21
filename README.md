# 👋 Welcome to My GitHub Profile!

I'm a **Software Engineer & Backend Developer** with 1.5+ years of professional experience building scalable, production-ready applications. I specialize in backend systems, microservices architecture, and full-stack development.

---

## 💼 Professional Summary

**Software Engineer | Backend Developer | Full-Stack Enthusiast**

Passionate about designing robust backend systems, optimizing performance, and writing clean, maintainable code. Experienced in building RESTful APIs, microservices architectures, and full-stack applications using modern tech stacks.

---

## 🛠️ Technical Skills

### **Languages**
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34C26?style=flat-square&logo=html5&logoColor=white)

### **Backend & Frameworks**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

### **Frontend & Frameworks**
![React.js](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)

### **Databases & Caching**
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### **Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=flat-square&logo=jira&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

### **Core Competencies**
- Data Structures & Algorithms
- Object-Oriented Programming (OOPs)
- Microservices Architecture
- RESTful API Design & Development
- System Design
- JWT Authentication & Security
- Redis Caching & Performance Optimization
- Message Queuing (RabbitMQ)

---

## 📌 Featured Projects

### 🔗 **[Journal Application](https://github.com/Soul-Hacker/journalApp)**
**Tech Stack:** Spring Boot, Maven, MongoDB, Spring Security, Redis, JWT

A production-ready **RESTful backend application** for journal management featuring:
- **Authentication & Authorization:** Role-based access control using Spring Security with JWT tokens and Bcrypt password hashing
- **Performance Optimization:** Implemented Redis caching layer to reduce database queries and improve response times
- **RESTful APIs:** Well-designed endpoints following REST conventions
- **Database:** Scalable MongoDB document-based architecture
- **User Management:** Admin-only user listing, role-based operations
- **Weather Integration:** Real-time weather greetings on user profile endpoint

**Key Features:**
- User registration and login with JWT
- Personal journal entry CRUD operations
- Admin dashboard for user management
- Email scheduler structure for weekly summaries
- Production-ready error handling

📍 [View Repository](https://github.com/Soul-Hacker/journalApp)

---

### 🍕 **[EatMania - Food Ordering Platform](https://github.com/Soul-Hacker/EatMania)**
**Tech Stack:** MERN Stack (MongoDB, Express, React, Node.js), Bcrypt.js

A full-stack **e-commerce platform** for food ordering featuring:
- **Dynamic UI:** Interactive and responsive user interface built with React.js
- **Secure Authentication:** User authentication with bcrypt.js password hashing
- **Scalable Backend:** RESTful APIs optimized for handling concurrent order requests
- **Real-time Order Processing:** Order management and tracking capabilities
- **Full-Stack Integration:** Seamless frontend-backend communication
- **User Dashboard:** Order history, favorites, and personalized recommendations

**Highlights:**
- Responsive design for desktop and mobile
- Payment integration ready
- Order status tracking in real-time
- User profile management

📍 [View Repository](https://github.com/Soul-Hacker/EatMania)

---

### 🎫 **[BMS - Booking Management System](https://github.com/Soul-Hacker/Bms)**
**Tech Stack:** Spring Boot, Java 17, MySQL, Redis, Spring Data JPA, Jedis

A sophisticated **movie booking system** showcasing advanced backend architecture:
- **Layered Architecture:** Clean separation of concerns with controllers, services, and repositories
- **Redis-based Seat Locking:** Optimistic seat reservation with distributed locking via Redis
- **Database Optimization:** JPA-based persistence with bulk operations for concurrent bookings
- **RESTful APIs:** Comprehensive endpoints for movie management and seat booking
- **Scalability:** Designed to handle concurrent booking requests efficiently

**Key Components:**
- Movie and show management
- Distributed seat locking with Redis
- Ticket generation and management
- Theatre and auditorium management
- Theater hierarchy: City → Theatre → Auditorium → Seats
- Bulk seat booking operations

**Architecture Highlights:**
- `MovieController` → `MovieServiceImpl` → `MovieRepository`
- `BookingController` → `RedisBookingService` → Multiple repositories
- `RedisService` for distributed locking and caching

📍 [View Repository](https://github.com/Soul-Hacker/Bms)

---

### 🎬 **[Reel Downloader - Instagram Media Extractor](https://github.com/Soul-Hacker/reel-downloader)**
**Tech Stack:** Spring Boot 3.2, Java 17, Thymeleaf, RapidAPI, Resilience4j

A feature-rich **web application** for downloading Instagram content with production-grade features:
- **Media Extraction:** Download Instagram Reels, Posts, and Videos
- **Rate Limiting:** Global (10 req/60s) + Per-IP (5 req/60s) protection via Resilience4j
- **SSRF Protection:** Secure proxy that validates only Instagram/Facebook CDN domains
- **Responsive UI:** Works seamlessly on desktop and mobile devices
- **Error Handling:** Comprehensive error handling with meaningful messages
- **Cloud Ready:** Docker and Google Cloud Run deployment support

**Advanced Features:**
- Dual-layer rate limiting for robustness
- Automatic cleanup of stale rate-limit entries
- REST API with intuitive endpoints
- Real-time rate limit status monitoring
- Configuration validation at startup
- Stream-based file downloads (no CORS issues)

**Tech Highlights:**
- Resilience4j for rate limiting
- RestTemplate with custom timeout configuration
- Thymeleaf templating engine
- Docker containerization
- Google Cloud Run deployment ready

📍 [View Repository](https://github.com/Soul-Hacker/reel-downloader)

---

### 📚 **[LLD - Low Level Design Concepts](https://github.com/Soul-Hacker/LLD)**
**Tech Stack:** Java, Design Patterns

A comprehensive **learning repository** documenting:
- Complete LLD (Low Level Design) concepts
- Design patterns implementation
- Object-oriented principles
- Real-world problem-solving approaches

Perfect for interview preparation and system design discussions.

📍 [View Repository](https://github.com/Soul-Hacker/LLD)

---

### 💻 **[Java-Based Projects Collection](https://github.com/Soul-Hacker/JavaBasedProjects)**
**Tech Stack:** Java, Core Concepts

A collection of **Java projects** demonstrating:
- Core Java concepts and best practices
- Problem-solving approaches
- Algorithm implementations
- Project structures and patterns

📍 [View Repository](https://github.com/Soul-Hacker/JavaBasedProjects)

---

### 💬 **[Chat Application](https://github.com/Soul-Hacker/ChatApp)**
**Tech Stack:** MERN Stack, Socket.io

A **real-time messaging platform** featuring:
- Real-time communication using Socket.io
- User-friendly chat interface
- Message history management
- Online status tracking

📍 [View Repository](https://github.com/Soul-Hacker/ChatApp)

---

## 🏆 Achievements & Coding Profiles

### **Competitive Programming Excellence**
| Platform | Achievement | Rating/Rank |
|----------|-------------|------------|
| **GeeksForGeeks** | College Rank **#2** | 450+ Problems Solved ⭐⭐⭐ |
| **LeetCode** | Consistent Problem Solver | 300+ Problems Solved 💯 |
| **CodeChef** | 3-Star Programmer | Max Rating: **1619** ⭐⭐⭐ |
| **TCS CodeVita Season 10** | Global Rank **2378** | Out of 100,000+ Participants 🌍 |

**What This Demonstrates:**
- Strong foundation in Data Structures & Algorithms
- Problem-solving mindset
- Ability to optimize solutions
- Consistency and dedication to continuous learning

---

## 📊 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Soul-Hacker&theme=dark&show_icons=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Soul-Hacker&theme=dark&layout=compact)

---

## 📚 What I'm Currently Learning

- Advanced System Design Patterns
- Cloud Platforms (AWS, GCP)
- Advanced Microservices Patterns
- Message Queue Systems

---

## 🔗 Connect With Me

- **Email:** hemantkrsaw291@gmail.com — Reach out anytime

---

## 💡 Open to Opportunities

I'm actively looking for:
- **Backend Development** roles focusing on microservices and system design
- **Full-Stack Development** positions with modern tech stacks
- **System Design** challenges and architectural discussions
- **Open Source Contributions** in backend frameworks

Feel free to reach out for:
- Technical discussions on system design
- Code reviews and collaboration
- Interview preparation guidance
- Project partnerships

---

## 📈 Project Highlights Summary

| Project | Type | Tech | Key Skills |
|---------|------|------|-----------|
| **JournalApp** | Backend API | Spring Boot, MongoDB, Redis | JWT Auth, Caching, REST APIs |
| **EatMania** | Full-Stack | MERN | Full-Stack Development, REST APIs |
| **BMS** | System Design | Spring Boot, MySQL, Redis | Distributed Locking, Scalability |
| **Reel Downloader** | Web App | Spring Boot, REST | Rate Limiting, Cloud Deployment |
| **LLD** | Educational | Java, Patterns | Design Patterns, System Design |

---

## 🎯 Key Strengths

✅ **Backend Excellence** — Building scalable, maintainable server-side applications
✅ **System Design** — Architecting solutions for real-world problems
✅ **Full-Stack Capability** — End-to-end development from frontend to database
✅ **Problem Solving** — Data structures, algorithms, and optimization
✅ **Code Quality** — Clean code practices, SOLID principles, design patterns
✅ **Performance Optimization** — Caching strategies, query optimization, concurrency handling

---

## 📖 Interview Preparation

My GitHub repositories serve as excellent resources for:
- **System Design Interviews** — Check BMS and Reel Downloader for real-world architectural patterns
- **Coding Interviews** — Visit LLD and JavaBasedProjects for algorithm and pattern knowledge
- **Behavioral Interviews** — Project documentation shows communication and problem-solving approach
- **Technical Depth** — Each project demonstrates mastery of specific technologies

---

⭐ **If you find my work interesting, please star my repositories!**

Last Updated: May 2026

---

## 🚀 Quick Start

Interested in exploring my work? Here's where to start:

1. **For System Design Insights** → Check [BMS](https://github.com/Soul-Hacker/Bms) and [Journal App](https://github.com/Soul-Hacker/journalApp)
2. **For Full-Stack Examples** → Explore [EatMania](https://github.com/Soul-Hacker/EatMania)
3. **For Production-Grade Features** → Review [Reel Downloader](https://github.com/Soul-Hacker/reel-downloader)
4. **For Learning Design Patterns** → Study [LLD](https://github.com/Soul-Hacker/LLD)

---

**Let's build something amazing together! 🚀**
