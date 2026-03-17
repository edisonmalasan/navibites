# NaviBites - SAMCIS Campus Food Delivery App

A comprehensive food delivery application designed for campus environments, featuring separate interfaces for customers, vendors, and admin.

## Quick Start

### Prerequisites

- **Node.js** (v20 or higher)
- **Docker** and **Docker Compose**
- **Git**

##  Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Running in Docker)
- **Security:** JSON Web Tokens (JWT), Bcrypt (Password Hashing)
- **Middleware:** CORS, Express Middleware
- **DevOps:** Docker, Docker Compose

---

## 📂 Project Structure

```text
NaviBites/
├── frontend/                # React frontend (Vite)
│   ├── .vite/               # Vite dependency cache
│   ├── public/              # Static assets
│   ├── src/                 # Application source code
│   ├── .gitignore           # Frontend ignored files
│   ├── components.json      # UI component configuration
│   ├── eslint.config.js     # Linting rules
│   ├── index.html           # SPA Entry point
│   ├── package.json         # Frontend dependencies & scripts
│   ├── tailwind.config.ts   # Tailwind CSS configuration
│   ├── tsconfig.json        # TypeScript configuration
│   └── vite.config.ts       # Vite configuration
├── server/                  # Express backend
│   ├── api/                 # API Route handlers
│   ├── middleware/          # Auth & validation middleware
│   ├── models/              # MongoDB/Mongoose schemas (User, Food, Order)
│   ├── scripts/             # Database seeding or maintenance scripts
│   ├── service/             # Business logic & DB interactions
│   ├── utility/             # Helper functions & constants
│   ├── .gitignore           # Backend ignored files
│   ├── Dockerfile           # Backend containerization
│   ├── package.json         # Backend dependencies & scripts
│   └── server.js            # Main entry point
├── .gitignore               # Root-level ignored files
├── README.md                # Project documentation
└── docker-compose.yaml      # Orchestrates Server & MongoDB containers
```

# SETUP

### 1. Clone the Repository

```bash
git clone https://github.com/edisonmalasan/campus-ordering.git
cd NaviBites
```

### 2. Frontend Setup 

```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start the Expo development server
npm run dev
```

### 3. Backend Setup 

```bash
# Navigate to server directory
cd server

# Install node dependencies
npm install

# Start Server
npm run
```


