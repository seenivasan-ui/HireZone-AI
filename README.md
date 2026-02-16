# 🚀 HireZone – AI-Based Career Preparation Platform

## 🌟 Project Overview

**HireZone** is a full-stack career preparation platform designed to help students and job seekers become **placement-ready**. Instead of using multiple websites for resumes, aptitude practice, and interview preparation, HireZone brings everything together into **one smart system**.

The platform focuses on improving a candidate’s **resume quality, problem-solving ability, and interview performance** through interactive tools and AI-assisted features.

🔧 Built as a **full-stack monorepo** with a React frontend and Node.js backend.

---

## ✨ Core Features

### 📄 Resume Analyzer
Upload your resume and receive insights like structure quality, missing skills, and improvement suggestions to make it more ATS-friendly.

### 🧠 Aptitude Practice Module
Practice quantitative, logical reasoning, and verbal questions with score tracking.

### 🎤 Interview Preparation
Access commonly asked HR and technical interview questions to build confidence.

### 🧑‍💻 Coding Practice Environment
Solve coding questions directly in the browser.

### 📊 Performance Tracking
Track quiz scores and improvement over time.

### 🎯 All-in-One Dashboard
Central hub for resume tools, aptitude practice, and interview preparation.

### 🎨 Modern User Interface
Clean and responsive UI built with modern frontend tools for a smooth user experience.

---

## 🛠 Technology Stack

### 💻 Frontend

| Technology       | Purpose                          |
|------------------|----------------------------------|
| React.js         | Frontend framework               |
| Vite             | Fast development build tool      |
| Tailwind CSS     | Styling                          |
| Shadcn UI        | UI components                    |
| Redux Toolkit    | State management                 |

### 🔧 Backend

| Technology       | Purpose                          |
|------------------|----------------------------------|
| Node.js          | Backend runtime                  |
| Express.js       | Server framework                 |
| MongoDB          | Database                         |
| Mongoose         | MongoDB object modeling          |

---

## 🎯 Target Users

- College students preparing for placements  
- Freshers looking for their first job  
- Job seekers improving interview skills  

---

## ⚙️ Getting Started

### ✅ Prerequisites

Make sure you have:

- Node.js (v18+)  
- Git  
- MongoDB (local or Atlas)  

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/hirezone.git
cd hirezone
```

---

#### 2. Frontend Setup

```bash
cd client
npm install
npm run dev
```

> The frontend should now be running at: [http://localhost:5173](http://localhost:5173)

---

#### 3. Backend Setup

```bash
cd ../server
npm install
touch .env
```

Add the following variables to your `.env` file:

```env
PORT=5000
MONGODB_URI=your_mongodb_atlas_connection_string_here
AUTH0_AUDIENCE=your_auth0_api_identifier_here
AUTH0_ISSUER_BASE_URL=https://your-auth0-domain.auth0.com/
```

Run the backend server:

```bash
npm run dev
```

> Your backend will run at: [http://localhost:5000](http://localhost:5000)

---

📈 Future Improvements

AI-powered resume scoring system

Role-based interview question generator

Timed mock aptitude tests

Detailed performance analytics

---
## 🤝 Contribution

We welcome all contributions!
If you have suggestions for features, improvements, or bug fixes:

- Open an issue
- Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.
