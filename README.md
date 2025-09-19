# 📌 TaskFlow – Full-Stack Kanban Board (In Progress)

![GitHub repo size](https://img.shields.io/github/repo-size/sahitya1903/taskflow)
![GitHub issues](https://img.shields.io/github/issues/sahitya1903/taskflow)
![GitHub stars](https://img.shields.io/github/stars/sahitya1903/taskflow?style=social)
![License](https://img.shields.io/badge/license-MIT-green)

TaskFlow is a **full-stack Kanban board application** that helps individuals and teams organize, track, and complete tasks efficiently.  
It provides a clean drag-and-drop interface, real-time updates, and collaboration features for effective project management.

---

## 🚀 Features (Planned & In Progress)
- ✅ **User Authentication** – JWT-based login/signup  
- ✅ **Task & Column Management** – Create, update, delete tasks & boards  
- 🔄 **Drag-and-Drop** – Move tasks between columns (In Progress)  
- ⏳ **Real-Time Updates** – Live task sync with Socket.IO  
- 📅 **Task Details** – Add due dates, labels, priorities  
- 📊 **Analytics Dashboard** – Track project progress  
- 👥 **Team Collaboration** – Assign tasks, invite members  

---

## ⚙️ Tech Stack
**Frontend:** React, Tailwind CSS / Material UI, Redux (or Context API)  
**Backend:** Node.js, Express.js  
**Database:** MongoDB / PostgreSQL  
**Authentication:** JWT, role-based access  
**Deployment:** Docker + AWS / Vercel / Render  

---

## 📂 Project Structure
```bash
TaskFlow/
│── client/ # React frontend
│── server/ # Express backend
│── database/ # Database models & migrations
│── docs/ # Documentation & diagrams
│── README.md
```

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/taskflow.git
cd taskflow
```

2. Setup Backend
```bash
cd server
npm install
npm run dev
```
3. Setup Frontend
```bash
cd client
npm install
npm start
```
4. Environment Variables

- Create a .env file in both client/ and server/ with the following:

```env
# Server
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

# Client
REACT_APP_API_URL=http://localhost:5000
```

## 🤝 Contributing
- Contributions are welcome!
- Fork the repo
- Create a new branch (feature/xyz)
- Commit your changes
- Open a Pull Request

## 📜 License
This project is licensed under the MIT License – feel free to use and modify.
