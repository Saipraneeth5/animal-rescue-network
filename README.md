# 🐾 Animal Rescue Network (Real-Time System)

A real-time platform for reporting, coordinating, and tracking animal rescue operations with role-based workflows and live updates.

---

## 🚀 Overview

Animal Rescue Network enables:

* 📍 Users to report rescue cases with geo-location and images
* 🙋 Volunteers to claim and respond to nearby cases
* 🛠️ Admins to monitor operations with system-wide visibility

The system focuses on **real-time coordination**, **faster response**, and **efficient rescue management**.

---

## 🧠 Key Features

* ⚡ Real-time case updates using WebSockets (Socket.IO)
* 🧭 Geo-tagged rescue reporting with urgency classification
* 👥 Role-based dashboards (Admin, Volunteer, User)
* 🏥 Smart hospital recommendation (top 3 based on proximity & availability)
* 💰 Donation tracking and case management APIs

---

## 🏗️ Architecture

This project follows a **microservice-style separation**:

```
animal-rescue-network/
│
├── frontend/   → React application (UI, dashboards)
├── backend/    → Node.js + Express (APIs, business logic)
```

---

## 🔗 Repositories

* 🎨 Frontend: https://github.com/Saipraneeth5/animal-rescue-network-frontend
* ⚙️ Backend: https://github.com/<your-username>/animal-rescue-network-backend

---

## ⚙️ Tech Stack

### Frontend

* React.js
* Redux Toolkit
* Axios
* Tailwind / CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.IO

---

## 🔄 System Flow

1. User reports a rescue case with location & image
2. Case is broadcasted in real-time to nearby volunteers
3. Volunteer claims the case
4. Admin monitors status and activity
5. System suggests nearest hospitals for treatment

---

## 🧪 Setup Instructions

### 1. Clone Main Repo

```
git clone https://github.com/<your-username>/animal-rescue-network.git
cd animal-rescue-network
```

### 2. Setup Backend

```
cd backend
npm install
npm start
```

### 3. Setup Frontend

```
cd ../frontend
npm install
npm start
```

---

## 🔐 Environment Variables

### Backend (`.env`)

```
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
```

### Frontend (`.env`)

```
REACT_APP_API_URL=http://localhost:5000
```

---

## 📈 Future Improvements

* 📊 Advanced admin analytics dashboard
* 🗺️ Map-based real-time tracking
* 🤖 AI-based rescue prioritization
* 📱 Mobile app integration

---

## 🎯 Why This Project Stands Out

Unlike basic CRUD apps, this system focuses on:

* Real-time communication
* Role-based system design
* Decision-making logic (hospital selection)

---

## 👨‍💻 Author

**Sai Praneeth**

* GitHub: https://github.com/Saipraneeth5
* LinkedIn: https://linkedin.com/in/saipraneeth-baira

---
