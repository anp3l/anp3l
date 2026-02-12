# Hi, I'm Andrea 👋

### Junior Software Developer

I am a recent Computer Science graduate, currently building my portfolio and sharpening my skills as a Junior Software Developer. My thesis focused on developing a video content management module for a web platform, and from that work I started an independent project to practice full-stack architecture in a real-world scenario.

- 🎓 Computer Science graduate (L-31), University of Turin.
- 🔭 Currently working on **Remote Video Platform**, a microservices-based video streaming system with Docker orchestration.
- 💻 Interested in modern web development (**Angular, Node.js**) and clean architecture.
- 🚀 Open to junior opportunities and collaborations.

---

### 🛠️ Tech Stack

**Frontend**  
![Angular](https://img.shields.io/badge/Angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Backend & Architecture**  
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**DevOps & Tools**  
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

**Architecture**  
![Microservices](https://img.shields.io/badge/Architecture-Microservices-success?style=for-the-badge)

---

## 📽️ Highlight Project: Remote Video Platform

A complete **video streaming platform** with microservices architecture, secure authentication, and Docker orchestration. Features dedicated Auth Server (JWT + refresh tokens), Video Server (FFmpeg/HLS transcoding), and Angular frontend with Material Design.

**🚀 Self-contained:** Deploy the entire stack locally with `docker-compose up --build`.

**Architecture:**
- Microservices design with dedicated Auth and Video services
- Docker containerization with health checks and restart policies
- MongoDB for user data, video metadata, and refresh tokens
- Stateless authentication with refresh token rotation

**Implemented Features:**
- **Secure Authentication**: RS256 JWT with automatic refresh (15min/7d)
- **Video Processing**: HLS adaptive streaming (1080p/720p/480p/360p)
- **Smart Frontend**: Preemptive token refresh, automatic retry on 401
- **Per-User Libraries**: Isolated video storage with metadata management
- **Background Transcoding**: Asynchronous FFmpeg processing with status polling
- **Responsive UI**: Grid/list view, search, filter, sort with Material Design

**Backend Capabilities (not yet in frontend UI):**
- Admin panel with user management
- Session management (list and revoke active sessions)
- Password reset flow with email templates
- User role system with audit logging

**Security:**
- RSA-signed JWT tokens (access + refresh) for authentication
- Refresh token rotation prevents replay attacks
- HMAC-signed temporary URLs for video stream access control
- Public/private key infrastructure for zero-trust service communication
- Per-user data isolation enforced by JWT claims

**Tech Stack:**
- **Frontend**: Angular 20, Material Design, Tailwind CSS, Video.js
- **Backend**: Node.js, Express, TypeScript, FFmpeg
- **Auth**: JWT (RS256), Refresh Tokens, Bcrypt
- **Database**: MongoDB
- **DevOps**: Docker, Docker Compose, Nginx

**🎯 Project Goal**  
To explore real-world full-stack patterns including microservices architecture, distributed authentication with refresh tokens, secure video streaming, and containerized deployment. The backend is feature-complete with admin capabilities, while the frontend focuses on core video library functionality.

**🔗 Main Repository:**  
[Remote Video Platform](https://github.com/anp3l/remote-video-platform) – Complete system with Docker orchestration, architecture documentation, and deployment guide

**📦 Individual Services:**
- [Auth Server](https://github.com/anp3l/auth-server) – RS256 JWT identity provider
- [Video Server](https://github.com/anp3l/remote-video-server) – FFmpeg transcoding & HLS streaming
- [Frontend Client](https://github.com/anp3l/remote-video-client) – Angular 20 UI with Video.js player

---

### 📫 How to reach me

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adr-peluso)
