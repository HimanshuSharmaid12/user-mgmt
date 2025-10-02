# 📝 User Management

This is a full-stack web application with **user authentication** (login/register), and a **protected dashboard** that allows CRUD operations on records with features like **multi-delete** and **edit modal**.

* Live Link - https://user-mgmt-f.vercel.app/

---

## 📂 Project Structure

```

root/
│── backend/    # Node.js + Express + MongoDB (API server)
│── frontend/   # React + Tailwind CSS (UI client)
│── README.md   # Project documentation

````

---

## ⚡ Features

- 🔐 **Authentication** – User Register & Login (JWT based)
- 🛡 **Protected Routes** – Dashboard only accessible when logged in
- 📊 **Dashboard Table** – Displays records with 6 columns:
  - Name, Email, Phone Number, Age, Father's Name
- ✏️ **CRUD Operations** – Create, Edit, Delete records
- ✅ **Multi-Select Deletion** of rows
- 🎨 **Responsive UI** with TailwindCSS

---

## 🛠 Tech Stack

**Frontend:**
- React (Vite)
- Tailwind CSS
- React Router DOM

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- bcryptjs (Password hashing)
- CORS + Helmet for security

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/HimanshuSharmaid12/user-mgmt.git
cd user-mgmt
````

---

### 2️⃣ Setup Backend (Node.js + MongoDB)

1. Navigate to the backend folder:

   ```bash
   cd backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the backend server:

   ```bash
   npm run dev
   ```

   Your backend will run at 👉 `http://localhost:3000`

---

### 3️⃣ Setup Frontend (React + Tailwind)

1. Navigate to the frontend folder:

   ```bash
   cd ../frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

   Your frontend will run at 👉 `http://localhost:5173`

---

## 🚀 Running the Project

* Start **backend** first (`http://localhost:3000`)
* Start **frontend** (`http://localhost:5173`)
* Open your browser and visit:
  👉 [http://localhost:5173](http://localhost:5173)

---

## 🔑 Default Pages

* `/` → Home Page
* `/register` → User Registration
* `/login` → User Login
* `/dashboard` → Protected Dashboard (requires login)

---

## 📌 Notes

* The required environment variables are already provided to run this project locally in your system. 

