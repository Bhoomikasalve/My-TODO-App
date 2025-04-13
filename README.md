# ✅ ToDo Full Stack App

A simple and intuitive full-stack ToDo application that lets users manage their daily tasks with ease. Built with modern technologies, this app allows users to add, update, complete, and delete tasks — with real-time updates and persistent storage.

---

## 🚀 Features

- ✅ User authentication (Sign up / Log in)
- 📋 Add, edit, and delete tasks
- 📌 Mark tasks as completed
- 🧹 Clear completed tasks
- 🌙 Light & Dark mode (optional)
- 💾 Persistent storage with database
- ⚡ Fast and responsive UI

---

## 🛠️ Tech Stack

**Frontend:**
- React.js / Next.js
- Tailwind CSS (or your styling choice)
- Axios / Fetch API

**Backend:**
- Node.js + Express.js
- MongoDB / PostgreSQL (via Mongoose / Prisma)

**Other Tools:**
- JWT for auth
- Dotenv for environment configs
- Git & GitHub for version control

---

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/todo-fullstack-app.git
cd todo-fullstack-app



cd backend
npm install
Create a .env file and add:


Copy
Edit
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
Start the backend server:

bash
Copy
Edit
npm run dev
3. Set up the Frontend
bash
Copy
Edit
cd ../frontend
npm install
Configure .env in frontend if needed:

ini
Copy
Edit
VITE_API_URL=http://localhost:5000
Start the frontend:

bash
Copy
Edit
npm run dev
