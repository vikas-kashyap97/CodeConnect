# 🚀 Code Connect

**Code Connect** is a full-stack web application designed to streamline technical interviews by allowing users to schedule, conduct, and record Zoom-based interviews — all within a single, intuitive platform.

🔗 [**Live Demo**](https://code-connect-video.vercel.app/) &nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; 💻 [**GitHub Repository**](https://github.com/vikas-kashyap97/CodeConnect.git)

---

## 📚 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## ✨ Features

- 🔒 **User Authentication** (Register/Login)
- 📅 **Schedule Interviews** with date, time, and participant details
- 🎥 **Zoom Integration** for seamless video interviews
- 💾 **Automatic Recording** and storage of interview sessions
- 📂 **Interview History** dashboard
- 🔎 **Search & Filter** past interviews
- 🌐 **Responsive Design** for both desktop and mobile

---

## 🛠 Tech Stack

**Frontend:**
- React.js
- Redux (State Management)
- Tailwind CSS / Material UI

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT (Authentication)

**APIs & Services:**
- Zoom API (Meetings & Recordings)
- Cloud Storage (AWS S3 / Cloudinary)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/code-connect.git
cd code-connect
```
### 2. Install dependencies
```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```
### 3. Set up environment variables
Create a .env file in both the client and server folders using the provided .env.example.

### 4. Run the app
```bash
# Start the client
cd ../client
npm start

# Start the server
cd ../server
npm run dev
```
### 🎯 Usage

- Register an account or log in.
- Connect your Zoom account.
- Schedule an interview by selecting date, time, and participants.
- Launch the interview directly within the app.
- Access and replay recordings from your interview history.
