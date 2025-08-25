# Codex

A full-stack coding contest platform where users can register, participate in coding contests, solve problems, and view leaderboards in real time.

---

## Features

- User authentication (signup/login)
- Create and manage coding contests
- Add and solve coding problems
- Real-time leaderboard
- Code execution and submission evaluation
- Responsive user interface

---

## Tech Stack

- **Frontend:** React, JavaScript, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas (cloud only)

---

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/codex.git
cd codex/V1
```

---

### 2. Database Setup

- Create a cluster at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- Create a database user and whitelist your IP address.
- Get your connection string, e.g.:
  ```
  mongodb+srv://<username>:<password>@<cluster-url>/
  ```

---

### 3. Backend Setup

```sh
cd backend
cp .env.example .env   # Or create .env as below
npm install
npm start
```

**.env example:**
```
MONGO=mongodb+srv://<username>:<password>@<cluster-url>/
PORT=5000
JWT_SECRET=your_jwt_secret
```

---

### 4. Frontend Setup

```sh
cd ../frontend
npm install
npm run dev
```

---

## Scripts

- **Backend:** `npm start`
- **Frontend:** `npm run dev`

---

**That’s it!**  
Update connection strings and secrets as needed.

