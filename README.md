<div align="center">

# ⚡ QUICKFORGE  

### _AI-Powered Creativity Engine for Effortless Content, Images & Ideas_


#### Powered by next-gen AI + modern full-stack engineering 🚀

![React](https://img.shields.io/badge/React-19.1.1-61DAFB?style=flat-square&logo=react&logoColor=black)
![Express](https://img.shields.io/badge/Express-5.1.0-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

### 🌐 [Live Demo](https://quick-forge-zckf.vercel.app)

</div>

---

## 🧩 Overview

**QuickForge** is an AI SaaS platform designed to supercharge your productivity and creativity.  
It merges powerful AI capabilities with a clean, responsive UI — helping you:

- ✍️ Write engaging articles & blogs  
- 🧠 Generate catchy titles instantly  
- 🎨 Create and edit AI-powered images  
- 📄 Get resume reviews & improvement tips  
- 👥 Explore a community of shared creations  

> Built on the PERN stack (PostgreSQL, Express, React, Node.js) with seamless authentication via **Clerk**, and image storage via **Cloudinary**.

---

## 🚀 Key Features

### 🤖 AI Tools
- 📝 **AI Article Generator** — Write SEO-friendly long-form content.  
- 💡 **Blog Title Generator** — Instantly ideate catchy headlines.  
- 🖼️ **Image Generation** — Transform prompts into art.  
- ✂️ **Background/Object Removal** — Clean up visuals instantly.  
- 📃 **Resume Review** — AI-driven feedback & score analysis.

### 👥 User Experience
- 🔐 **Authentication via Clerk**
- 🏠 **Dashboard** with quick-access tools  
- 💬 **Community Feed** to explore others’ creations  
- 📱 **Responsive UI** built with Tailwind  
- ⚡ **Instant API responses** via Express  

### 🧱 Infrastructure
- ☁️ **Cloudinary** for secure uploads  
- 🧩 **PostgreSQL (Neon)** for scalable data storage  
- 🔄 **OpenAI / Gemini API** for smart generation  
- 🧾 **Clerk Billing** for plan-based access control  

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React 19, Vite, TailwindCSS, Axios, React Router |
| **Backend** | Node.js, Express 5, PostgreSQL, Clerk, Cloudinary |
| **Database** | Neon PostgreSQL |
| **Auth & Billing** | Clerk |
| **AI Engine** | Gemini / OpenAI |
| **Deployment** | Vercel |
| **File Handling** | Multer, Cloudinary API |

---

## 🏗️ Architecture

```bash
QuickForge/
├── client/              # Frontend (React + Vite)
│   ├── src/
│   │   ├── pages/       # Views (Dashboard, Tools, Community)
│   │   ├── components/  # Reusable UI components
│   │   └── assets/
│   └── vite.config.js
│
├── server/              # Backend (Express + PostgreSQL)
│   ├── routes/          # API Endpoints
│   ├── controllers/     # Business Logic
│   ├── configs/         # Cloudinary, DB, etc.
│   ├── middlewares/     # Auth middleware
│   └── server.js
│
└── vercel.json          # Vercel deployment config
