# 🏏 CricHub - Cricket Club Management System

![CricHub Logo](./Capture-removebg-preview.png)

CricHub is a **Cricket Club Management System** built using the **MERN stack** to efficiently manage clubs, players, and administrators. It streamlines operations for cricket organizations by providing tools for **team management, match tracking, and player statistics**.

## 🚀 Features

✅ Club and player management  
✅ Role-based authentication (System Admin, Club Admin, Users)  
✅ Cricket scoreboard and match tracking  
✅ News and announcements for clubs  
✅ User-friendly dashboard  

---

## 🛠 Tech Stack

- **Frontend:** React.js, Redux, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JSON Web Tokens (JWT)  
- **Deployment:** Vercel (Frontend), Render (Backend)  

---

## 📂 Repository Structure

This project is divided into three repositories:

1. **Client** – Frontend built with React.js  
   🔗 [GitHub Repository](https://github.com/Crichub/client)  

2. **Admin** – Admin dashboard for managing clubs  
   🔗 [GitHub Repository](https://github.com/Crichub/admin)  

3. **API** – Backend server using Express.js  
   🔗 [GitHub Repository](https://github.com/Crichub/api)  

---

## 🔧 Installation & Setup

### Prerequisites:
- Install **Node.js** and **MongoDB**
- Clone the repositories:

\`\`\`bash
git clone https://github.com/your-username/client.git
git clone https://github.com/your-username/admin.git
git clone https://github.com/your-username/api.git
\`\`\`

### Backend Setup:
\`\`\`bash
cd api
npm install
cp .env.example .env  # Update environment variables
npm start
\`\`\`

### Frontend Setup:
\`\`\`bash
cd client
npm install
npm start
\`\`\`

### Admin Panel Setup:
\`\`\`bash
cd admin
npm install
npm start
\`\`\`

## 👨‍💻 Contribution Guide

### Team Members:
- **K.D.H.P. Kothalawala** – Full Stack Developer ([GitHub](https://github.com/yourusername))  
- **A.W.M.N.P. Wijesinghe** – Backend Developer  
- **M.R.K.M. Rathnayaka** – Frontend Developer  
- **R.A.G. Karunarathna** – Frontend Developer  

### Collaboration Guidelines:
- Use **GitHub Issues** for reporting bugs.  
- Follow the **feature branch workflow** (\`feature/your-feature\`).  
- Submit **pull requests (PRs)** for review before merging.  

## 📌 Usage

1. **System Admin** creates **Club Admin** accounts.  
2. **Club Admins** manage players, schedules, and news.  
3. **Users** can view match updates, news, and scoreboards.  

🔗 **Live Demo:** Coming Soon  

## 📡 API Documentation

| Endpoint            | Method | Description                |
|---------------------|--------|----------------------------|
| \`/api/auth/login\`   | POST   | Login a user               |
| \`/api/clubs\`        | GET    | Fetch all clubs            |
| \`/api/players\`      | GET    | Fetch player details       |
| \`/api/matches\`      | GET    | Get match statistics       |

📄 **Full API docs:** Coming Soon  

## 📜 License & Acknowledgments

📜 This project is licensed under the **MIT License**.  
Special thanks to all contributors and the **Open Source Community**!"
