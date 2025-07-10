# 🏫 School Management System (MERN)

A full-stack **MERN-based School Management System** with separate dashboards for **Admin**, **Teacher**, and **Student**.

---

## ✅ Features

### 👨‍🏫 Admin:
- Register/login as admin
- Add/edit/delete students & teachers
- Assign homework
- Create/manage classes
- Post announcements
- Add/view books in the library
- Mark/view attendance
- View submitted assignments

### 👩‍🏫 Teacher:
- Sign in
- View student list
- Assign homework
- Mark attendance
- Post exams and events
- View classes and performance

### 👨‍🎓 Student:
- View announcements
- View & submit assignments
- View attendance
- View available books in library
- View exams & events

---

## 🛠 Tech Stack

| Part       | Technology                 |
|------------|----------------------------|
| Frontend   | React + Vite               |
| Backend    | Node.js + Express          |
| Database   | MongoDB + Mongoose         |
| Others     | Axios, React Router, CORS, Dotenv |

---

## 🚀 Getting Started (Development)

Follow the steps below to set up the project on your local machine.

---

### 📁 1. Clone the Repository

```bash
git clone https://github.com/hemavijayalakshmi/SCHOOL-MANAGEMENT-SYSTEM.git
cd SCHOOL-MANAGEMENT-SYSTEM

## 🔧 2. Run the Backend

```bash
cd backend
npm install
npm start

📄 **Create `.env` file inside the `/backend` folder:**

```env
PORT=4000
MONGODB_URI=mongodb+srv://Hema:Hema1234@cluster0.z2y8v.mongodb.net/MERN_STUDENT_MANGEMENT_SYSTEMretryWrites=true&w=majority&appName=Cluster0
FRONTEND_URL=http://localhost:5173


## 💻 3. Run the Frontend

Open a new terminal window and run:

```bash
cd frontend
npm install
npm run dev
