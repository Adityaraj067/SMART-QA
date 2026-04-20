# 🚀 SMART-QA

SMART-QA is a full-stack real-time Question & Answer platform that allows users to create, join, and participate in interactive rooms. It integrates AI-powered responses to enhance user experience and provide intelligent answers.

---

## 🧠 Features

* 🔐 User Authentication (Register/Login)
* 🏠 Create & Join Rooms
* 💬 Real-time Q&A Interaction
* 🤖 AI-powered Answer Generation (Gemini API)
* 🔄 Socket-based Communication
* 📦 RESTful APIs
* ⚡ Fast frontend using React + Vite

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* JavaScript
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Other Tools

* Socket.io
* Mongoose
* dotenv

---

## 📁 Project Structure

```
SMART-QA
├── smartqa-server        # Backend (Node.js + Express)
├── smartqa-react-client # Frontend (React + Vite)
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 Clone Repository

```
git clone https://github.com/Adityaraj067/SMART-QA.git
cd SMART-QA
```

---

### 🔹 Backend Setup

```
cd smartqa-server
npm install
```

Create a `.env` file in `smartqa-server` and add:

```
MONGO_URI=your_mongodb_connection_string
PORT=5001
```

Run backend:

```
npm start
```

---

### 🔹 Frontend Setup

Open a new terminal:

```
cd smartqa-react-client
npm install
npm start
```

---

## 🌐 Application URLs

* Frontend: http://localhost:3000
* Backend: http://localhost:5001

---

## 🔐 Environment Variables

| Variable  | Description               |
| --------- | ------------------------- |
| MONGO_URI | MongoDB connection string |
| PORT      | Server port number        |

---

## 🚀 Future Improvements

* ✅ Better UI/UX
* 🔔 Notifications system
* 📊 Analytics dashboard
* 🌍 Deployment (AWS / Vercel / Render)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Aditya Raj Pandey**

* GitHub: https://github.com/Adityaraj067

---

⭐ If you like this project, don’t forget to give it a star!
