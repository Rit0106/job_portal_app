# 🚀 Job Portal App
A full-stack **Job Portal Application** built with **React (Vite)** for the frontend and **Node.js + Express** for the backend.  
The goal is to provide a platform where employers can post jobs and job seekers can browse and apply.

---

## 🧰 Tech Stack
- **Frontend:** React 18, Vite, React DOM  
- **Backend:** Node.js, Express.js, CORS  
- **API:** REST endpoints for communication  
- **Styling:** (Planned: TailwindCSS / Bootstrap)  
- **Database:** (Planned: MongoDB / PostgreSQL)  

---

## ⚡ Getting Started

### 1️⃣ Clone the repository
git clone https://github.com/Rit0106/job_portal_app.git  
cd job_portal_app  

### 2️⃣ Backend Setup
cd backend  
npm install  
npm start  

➡ Backend runs at: http://localhost:5000/  

### 3️⃣ Frontend Setup
Open a new terminal at project root:  
cd frontend  
npm install  
npm run dev  

➡ Frontend runs at: http://localhost:5173/ (Vite default)  

ℹ️ If ports are busy, Vite/Node will suggest another port in the terminal.

---

## 🛠 Scripts

**Backend**  
- npm start → start express server  

**Frontend**  
- npm run dev → start development server  
- npm run build → production build  
- npm run preview → preview production build locally  

---

## 🔌 API (Current & Planned)

**Current**  
- GET / → returns: Job Portal Backend is running 🚀  

**Planned**  
- POST /api/auth/register → create account  
- POST /api/auth/login → login (JWT)  
- GET /api/jobs → list jobs  
- POST /api/jobs → create job (employer)  
- POST /api/jobs/:id/apply → apply to a job (seeker)  

---

## ✨ Features

**Now**  
- Minimal Express backend + CORS enabled  
- Minimal React app scaffolded via Vite  

**Next**  
- Authentication (JWT), role-based access (Admin/Employer/Seeker)  
- CRUD for job listings  
- Applications dashboard for seekers & employers  
- Database integration (MongoDB / PostgreSQL)  

---

## 🧪 Quick Health Check
- Open http://localhost:5000/ → should show: "Job Portal Backend is running 🚀"  
- Open http://localhost:5173/ → should show the React landing page  

---

## 🧩 Troubleshooting

- ENOENT: no such file or directory, open '.../package.json'  
  → You’re likely in the wrong folder. Run `dir` (Windows) or `ls` and ensure you are inside /backend or /frontend before npm install.  

- fatal: remote origin already exists  
  → Run:  
    git remote -v  
    git remote set-url origin https://github.com/<your-username>/job_portal_app.git  

- 403 push denied (wrong GitHub account)  
  → Make sure you have write access or change remote to your fork. Use a PAT or gh auth login.  

---

## 🤝 Contributing
1. Fork the repo  
2. Create a feature branch → git checkout -b feature/my-feature  
3. Commit your changes → git commit -m "feat: add my feature"  
4. Push and open a Pull Request 🎉  

---

## 📝 License
This project is licensed under the **MIT License**.  

---

## 👤 Author
**Owner:** [@Rit0106](https://github.com/Rit0106)  
Issues, ideas, and contributions are welcome!
