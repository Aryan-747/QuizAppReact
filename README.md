# Quiz Application

A full-stack quiz web application built with **Node.js**, **Express**, **React**, and **TypeScript**. Users can take quizzes, view results, and track performance through a sleek and responsive interface.

## 🗂 Project Structure

quiz-app/
├── backend/ # Node.js + Express server
├── frontend/ # React + TypeScript client

yaml
Copy
Edit

## 🚀 Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn
- MongoDB (for backend)

---

### 🔧 Setup Backend

```bash
cd backend
npm install
# or
yarn install
➕ Create a .env file in backend/ with:
env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
▶️ Start the backend server:
bash
Copy
Edit
npm run dev
# or
yarn dev
💻 Setup Frontend
bash
Copy
Edit
cd frontend
npm install
# or
yarn install
▶️ Start the frontend app:
bash
Copy
Edit
npm start
# or
yarn start
The frontend runs on http://localhost:3000 and connects to the backend on http://localhost:5000
