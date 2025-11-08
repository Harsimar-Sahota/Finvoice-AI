# 🧾 Finvoice AI

### **AI-Powered Invoice Generator & Finance Assistant (MERN + Gemini AI)**

**Finvoice AI** is a full-stack, AI-driven invoicing and finance automation platform.
It converts plain text (emails, messages, or receipts) into professional invoices, sends automated payment reminders, and generates insightful financial summaries — all powered by **Google Gemini AI**.

✅ Built with the **MERN Stack**
✅ Enhanced with **Docker** + **CI/CD Pipelines**
✅ Secured via **JWT Authentication**
✅ Tested with **Jest**

---

## 🌐 Live Demo

🔗 **App URL:** *[Add your deployed link]*
🔐 **Test Credentials:**

```
email: demo@finvoice.ai  
password: Demo@123
```

🎥 **90-Second Demo Video:** *[Add your Loom or YouTube link]*

---

## 🖼️ Screenshots

(Add 3–5 screenshots here)

* Dashboard Overview
* Create Invoice
* AI-Generated Invoice
* AI Payment Reminder
* Profile Settings

---

## 🧠 Overview

Finvoice AI helps freelancers and small businesses automate invoicing and payment management with AI.
It integrates Google Gemini to **parse unstructured text into structured invoices**, provides **reminder emails**, and visualizes revenue insights through a clean dashboard.

---

## 🛠️ Tech Stack

| Layer                  | Technology                         |
| ---------------------- | ---------------------------------- |
| **Frontend**           | React (Vite) + TailwindCSS + Axios |
| **Backend**            | Node.js + Express.js               |
| **Database**           | MongoDB Atlas                      |
| **AI Engine**          | Google Gemini API (@google/genai)  |
| **Authentication**     | JWT + bcryptjs                     |
| **Containerization**   | Docker                             |
| **CI/CD**              | GitHub Actions                     |
| **Testing**            | Jest                               |
| **Environment Config** | dotenv                             |

---

## ✨ Features

### 🔐 Authentication

* Secure signup/login using JWT
* Password hashing with bcrypt

### 🧾 Invoice Management

* Create, edit, delete, and filter invoices
* Auto-filled business details
* Export invoices as PDF

### 🧠 AI-Powered Tools

* **AI Invoice Generator:** Convert text → invoice instantly
* **AI Reminder Emails:** Generate payment reminders
* **AI Dashboard:** Summarize income, due payments, and insights

### 📱 Modern UI

* Responsive React + Tailwind design
* Dark mode ready

---

## 🏗️ Architecture Diagram

*(Add your PNG image here — generated with draw.io, Excalidraw, or Miro)*

Example:

```
Client (React)  →  Express API  →  Gemini AI Service  →  MongoDB
```

---

## 📂 Project Structure

```
Finvoice-AI/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
├── .github/workflows/     # CI/CD pipelines
├── docker-compose.yml     # Docker setup
├── .env.example
└── README.md
```

---

## ⚙️ Installation & Setup

### 🧩 Clone Repository

```bash
git clone https://github.com/Harsimar-Sahota/Finvoice-AI.git
cd Finvoice-AI
```

---

### 🖥️ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the **backend** folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
GEMINI_MODEL=models/gemini-2.5-flash
PORT=8000
```

Run backend:

```bash
npm run dev
```

---

### 💻 Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

Visit:
👉 [http://localhost:5173](http://localhost:5173)

---

## 🐳 Docker Setup

### Build & Run

```bash
docker-compose up --build
```

App runs on:

* Frontend → `http://localhost:5173`
* Backend → `http://localhost:8000/api`

*(Update your Dockerfiles to expose ports 5173 & 8000)*

---

## 🔄 Continuous Integration / Deployment (CI/CD)

This project uses **GitHub Actions** for:

* Automated builds
* Jest tests
* Docker image build
* Auto-deployment to production

Add your badge here after setup:
`![CI](https://github.com/Harsimar-Sahota/Finvoice-AI/actions/workflows/main.yml/badge.svg)`

---

## ✅ Testing (Jest)

Finvoice AI uses **Jest** for unit testing.

### 📋 Coverage

* Auth API tests (login/signup)
* AI generation tests (mocked Gemini API)
* Invoice CRUD logic
* Utility functions (date, parsing)

Run tests:

```bash
cd backend
npm run test
```

Optional:

```bash
npm run test:watch
```

---

## 📈 Scaling Plan

| # | Strategy                                  | Purpose                |
| - | ----------------------------------------- | ---------------------- |
| 1 | Add **rate limiting** on AI endpoints     | Prevent API abuse      |
| 2 | Use **Redis queues** for heavy AI tasks   | Handle concurrency     |
| 3 | Implement **MongoDB indexing**            | Faster invoice queries |
| 4 | Serve frontend via **CDN**                | Faster global load     |
| 5 | Store files in **AWS S3**                 | Offload from server    |
| 6 | Use **Redis caching** for dashboard stats | Improve performance    |

---

## 🔐 Security Practices

* JWT-based authentication
* Password hashing (bcrypt)
* Input validation (Zod/Joi)
* Rate limiting on AI routes
* CORS + Helmet middleware
* Environment secrets via `.env`
* No secrets committed to repo

---

## 💡 Inspiration

> Inspired by **Y Combinator’s RFS**: *Vertical SaaS & AI Tools for Small Businesses*

This project aligns with Y Combinator’s mission of building AI tools that automate real business workflows.

---

## 👨‍💻 Author

**Harsimar Preet Singh Sahota**
Full Stack Developer — MERN + AI

🌐 [GitHub](https://github.com/Harsimar-Sahota)
💼 [LinkedIn](https://linkedin.com/in/your-link)

---

## 🪪 License

This project is open-source under the **MIT License**.

---

Would you like me to generate those **next** so your repo becomes fully production-ready on GitHub?
