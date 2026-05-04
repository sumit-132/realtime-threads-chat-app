# 💬 Realtime Threads Chat Application

A full-stack, production-style realtime chat and discussion platform built with modern web technologies. This application supports **threads, replies, realtime messaging, and notifications**, along with secure authentication and scalable backend architecture.

---

## 🚀 Overview

This project demonstrates a complete full-stack system with:

* Realtime chat using WebSockets
* Thread-based discussion system
* Authentication & protected routes
* Notifications system
* Scalable backend + database architecture

---

## ✨ Core Features

### 🧵 Threads & Discussions

* Create and explore threads
* Reply to discussions
* Like and interact with content

---

### 🔐 Authentication & Security

* Secure authentication using Clerk
* Protected routes (frontend + backend)
* User session management

---

### 💬 Realtime Chat

* Live messaging system (Socket.io)
* Online/offline user presence
* Typing indicators
* Instant message delivery

---

### 🔔 Realtime Notifications

* Instant alerts for:

  * Replies
  * Likes
  * Messages
* Real-time updates using sockets

---

### 🖼 Media Upload

* Image upload using Cloudinary
* Attach images in chat and threads

---

### 🗄 Database & Backend

* PostgreSQL database
* Docker-based local setup
* Clean backend architecture
* API layer separation

---

### 🌐 Frontend UI

* Built with Next.js (App Router)
* Responsive modern UI
* Dark theme support
* Component-based structure

---

## 🧱 Tech Stack

### Frontend

* Next.js (App Router)
* React
* Tailwind CSS

### Backend

* Node.js
* Express.js
* Socket.io

### Database

* PostgreSQL

### Tools & Integrations

* Clerk (Authentication)
* Cloudinary (Media uploads)
* Docker (Containerized DB)

---

## 📂 Project Structure

```
realtime_threads_chat_app
│
├── frontend/        # Next.js frontend
├── backend/         # Node.js + Express backend
├── docker-compose.yml
├── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/realtime-threads-chat-app.git
cd realtime-threads-chat-app
```

---

### 2️⃣ Setup Backend

```bash
cd backend
npm install
npm run dev
```

---

### 3️⃣ Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

---

### 4️⃣ Run Database (Docker)

```bash
docker-compose up -d
```

---

## 🔑 Environment Variables

Create `.env` files in both frontend and backend directories.

### Example:

#### Backend `.env`

```
DATABASE_URL=your_postgres_url
CLERK_SECRET_KEY=your_secret_key
CLOUDINARY_URL=your_cloudinary_url
```

#### Frontend `.env`

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000
```

---

## 🔄 Application Flow

1. User signs up / logs in
2. Creates or browses threads
3. Interacts via replies and likes
4. Sends realtime messages
5. Receives instant notifications
6. Backend handles API + realtime events

---

## 🧠 Architecture Highlights

* Separation of frontend, backend, and realtime layers
* Socket-based communication for live updates
* Containerized database using Docker
* Modular and scalable structure

---

## 🚀 Future Enhancements

* Message encryption
* Group chat support
* Push notifications
* Deployment (AWS / Vercel / Render)
* Performance optimization

---

## 👨‍💻 Author

**Sumit Sahoo**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
