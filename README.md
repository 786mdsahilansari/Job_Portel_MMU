
---

## 💼 Job Portal Management System

A **MERN Stack-based Job Portal** application that allows users to register, login, view job listings, and apply for jobs. Admins can manage job types, job listings, and user data.

---

### 📁 Project Structure

```
├── backend/
│   ├── controllers/      → Logic for auth, jobs, users
│   ├── middleware/       → Auth & error handling
│   ├── models/           → Mongoose schemas for job, user, jobType
│   ├── routes/           → All backend APIs (auth, jobs, jobTypes, users)
│   ├── utils/            → Utility functions (e.g. token, validators)
│   ├── app.js            → Main Express.js server setup
│   └── .env              → Environment variables
│
├── frontend/
│   ├── public/           → Public static files
│   ├── src/              → React source code
│   └── build/            → Production-ready build folder
│
├── package.json          → Backend dependencies
├── frontend/package.json → Frontend dependencies
```

---

### ⚙️ Features

* User Registration & Login (JWT Auth)
* Role-based access (Admin/User)
* Post and apply for jobs
* Job Type categorization
* Protected routes using middleware
* Fully responsive frontend in React
* Environment variables with `.env`

---

### 🚀 How to Run (Local Setup)

> Make sure you have Node.js and MongoDB installed on your system.

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/786mdsahilansari/Job_Portel_MMU.git
cd Job_Portel_MMU
```

---

#### 2️⃣ Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside `/backend` and add:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm start
```

---

#### 3️⃣ Setup Frontend

```bash
cd frontend
npm install
npm start
```

Frontend will run on `http://localhost:3000`

---

---

### 🙌 Author

**Md Sahil Ansari**
📧 [786mdsahilansari@gmail.com](mailto:786mdsahilansari@gmail.com)
📞 +91-8969344814
🔗 [GitHub Profile](https://github.com/786mdsahilansari)

---

