# 🍔 NaviBites - SAMCIS Campus Food Delivery App

A comprehensive food delivery application designed for campus environments, featuring separate interfaces for customers, vendors, and admin.

## 🚀 Quick Start

### Prerequisites

- **Node.js** (v20 or higher)
- **Docker** & **Docker Compose**
- **Git**

## 💻 Tech Stack

### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

### Database & DevOps
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### Security & Others
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Bcrypt](https://img.shields.io/badge/Bcrypt-black?style=for-the-badge)

---

## 📂 Project Structure

```text
campus-ordering-system/
├── frontend/                # React frontend (Vite)
│   ├── public/              # Static assets
│   ├── src/                 # Application source code
│   ├── index.html           # SPA Entry point
│   ├── package.json         # Frontend dependencies & scripts
│   ├── tailwind.config.ts   # Tailwind CSS configuration
│   └── vite.config.ts       # Vite configuration
├── server/                  # Express backend
│   ├── api/                 # API Route handlers
│   ├── middleware/          # Auth & validation middleware
│   ├── models/              # MongoDB/Mongoose schemas
│   ├── service/             # Business logic & DB interactions
│   ├── Dockerfile           # Backend containerization
│   ├── package.json         # Backend dependencies & scripts
│   └── server.js            # Main entry point
├── README.md                # Project documentation
└── docker-compose.yaml      # Orchestrates Server & MongoDB containers
```

## 🛠 SETUP

### 1. Clone the Repository

```bash
git clone https://github.com/edisonmalasan/campus-ordering.git
cd campus-ordering
```

### 2. Frontend Setup

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start the Vite development server
npm run dev
```

### 3. Backend Setup

```bash
# Navigate to server directory
cd server

# Install node dependencies
npm install

# Start Server (Development mode)
npm run dev
```

