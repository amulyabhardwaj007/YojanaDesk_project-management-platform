
# 🚀 YojanaDesk – AI-Driven Project Management Platform



> **YojanaDesk** transforms how teams collaborate—by combining AI-powered task management, GitHub automation, real-time chat, and analytics dashboards in one unified experience.

  
📦 **Source Code**: [github.com/amulyabhardwaj007/YojanaDesk_project-management-platform](https://github.com/amulyabhardwaj007/YojanaDesk_project-management-platform)

---

## 🧠 Why YojanaDesk?

From daily standups to shipping releases, teams need tools that *stay out of their way and scale with them*. YojanaDesk does just that:

- ✅ Smart AI task assignments
- ✅ GitHub-synced progress tracking
- ✅ Real-time WebSocket chat
- ✅ Visual dashboards to avoid bottlenecks
- ✅ RBAC for secure, scoped access
- ✅ Beautiful, responsive UI

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🎯 **AI Task Management** | Assigns tasks based on availability & performance |
| 🐙 **GitHub Integration** | Auto-updates tasks via commits & PRs |
| 💬 `Live Chat `&` Video call ` | Real-time WebSocket-based messaging |
| 📊 **Analytics Dashboard** | Visual timeline, KPIs, and team stats |
| 🔐 **Role-Based Access** | PMs, Leads, and Members—each with tailored tools |
| 🔔 **Instant Notifications** | Snackbar alerts for assignments & status |

---

## 🧪 Tech Stack

| Layer | Technologies |
|-------|--------------|
| **Frontend** | React.js · Tailwind CSS · Framer Motion · Material UI |
| **Backend** | Node.js · Express · GraphQL |
| **Database** | MongoDB (Mongoose ODM) |
| **Realtime** | WebSockets · WebRTC (Chat & Notifications) |
| **Auth** | JWT · OAuth2 (Google Login support coming soon!) |

---

## 📸 Screenshots

### 🖥️ Dashboard  
![Dashboard](/docs/assets/dashboard.png)

### 📋 Task Management  
![Tasks](/docs/assets/Task.png)

### 💬 Chat Room  
![Chat](/docs/assets/Chat.png)

---

### Video Call
![Video Call](/docs/assets/VideoCall.png)

### GitHub
![GitHub](/docs/assets/GitHub.png)

### Team Structure
![Team Structure](/docs/assets/Structure.png)

### Analytics
![Analytics](/docs/assets/Analytics.png)





## ⚙️ Getting Started

Ready to run locally? Here's how:

```bash
# Clone the repository
git clone https://github.com/amulyabhardwaj007/project-management-tool.git
cd project-management-tool

# Install dependencies
npm install

# Start the development server
npm run dev
````
Backend .env

```bash
MONGO_URI=
PORT
JWT_SECRET=a
EMAIL= 
PASSWORD=
FRONTEND_URL=https://project-management-tool-two-jet.vercel.app

STUN_SERVER=

# Optional video call settings
MAX_PARTICIPANTS_PER_ROOM=8
MEETING_TIMEOUT_MINUTES=120

GITHUB_WEBHOOK_SECRET=   

# APP_URL=https://your-deployed-app.com (for production).

GEMINI_API_KEY=

NODE_ENV=

````

Frontend .env

```bash
BACKEND_URL=
VITE_SOCKET_URL=
REACT_APP_QUICK_EMAIL_API_KEY=
REACT_APP_BACKEND_URL=
REACT_APP_BACKEND_WS_URL=
NODE_ENV=
````

> 🧩 Make sure to create a `.env` file at the root and add required environment variables:

* `MONGODB_URI`
* `JWT_SECRET`
* `GITHUB_WEBHOOK_SECRET`
* etc.

---

## 👥 User Roles

| Role                      | Responsibilities                                          |
| ------------------------- | --------------------------------------------------------- |
| 👨‍💼 **Project Manager** | Create projects, assign leads, monitor performance        |
| 🧑‍💻 **Team Lead**       | Manage sub-teams, delegate tasks, approve work            |
| 👤 **Team Member**        | Complete tasks, sync GitHub activity, communicate updates |

---

## 💡 Best Practices

* ⚖️ Review AI task suggestions regularly for balance
* 🔄 Keep GitHub webhooks active for real-time sync
* 📈 Use analytics to identify & resolve bottlenecks early
* 💬 Encourage async & real-time team discussions
* 🔐 Audit permissions monthly for team security

---

## 🙌 Contributors

Built with ❤️ by [@AmulyaBhardwaj](https://github.com/amulyabhardwaj007)
Special thanks to [@SumitAttri](https://github.com/Sumiattri) for collaboration and core contributions!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
Fork it. Star it. Build on it. 🚀

---


