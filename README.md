# Opportunity Job Portal 🚀

A full-stack **Job Portal Web Application** that connects **job seekers** with **recruiters/companies**. The platform supports job posting, job search, applications, authentication, and role-based access using a modern tech stack.

---

## ✨ Features

### 👨‍💼 Job Seekers

* User authentication (Register / Login)
* Browse and search jobs
* Apply for jobs
* View applied jobs
* Profile management

### 🏢 Recruiters / Companies

* Company registration & profile management
* Post new job openings
* Manage posted jobs
* View applicants for a job

### 🔐 Authentication & Security

* JWT-based authentication
* Role-based authorization (Student / Recruiter)
* Protected routes

### ⚡ UI & State Management

* Responsive UI with Tailwind CSS
* Centralized state management using Redux Toolkit
* API integration using Axios

---

## 🛠 Tech Stack

### Frontend

* React (Vite)
* Redux Toolkit
* Tailwind CSS
* Axios

### Backend *(if applicable)*

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

---

## 📁 Project Structure

```
Opportunity-Job-Portal
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── redux
│   │   │   ├── authSlice.js
│   │   │   ├── jobSlice.js
│   │   │   ├── companySlice.js
│   │   │   ├── applicationSlice.js
│   │   │   └── store.js
│   │   ├── utils
│   │   ├── RootLayout.jsx
│   │   └── main.jsx
│   ├── tailwind.config.js
│   └── vite.config.js
│
└── backend *(optional)*
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js (v18+ recommended)
* npm or yarn
* MongoDB (local or cloud)

---

### 🔧 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The frontend will run at:

```
http://localhost:5173
```

---

### 🔧 Backend Setup *(if present)*

```bash
cd backend
npm install
npm start
```

Create a `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint               | Description   |
| ------ | ---------------------- | ------------- |
| POST   | /api/auth/register     | Register user |
| POST   | /api/auth/login        | Login user    |
| POST   | /api/job/create        | Create job    |
| GET    | /api/job               | Get all jobs  |
| POST   | /api/application/apply | Apply for job |

---

## 🧪 Testing

* Manual testing via UI
* API testing using Postman

---


## 📌 Future Enhancements

* Resume upload & parsing
* Job recommendations
* Admin dashboard
* Email notifications
* Advanced filters

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Prashant Yadav**

* GitHub: [https://github.com/Prashant12301](https://github.com/Prashant12301)

---

⭐ If you like this project, don’t forget to give it a star!
