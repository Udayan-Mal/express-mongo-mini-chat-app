# Express Mongo Mini Chat App

A simple chat application built using **Node.js**, **Express.js**, and **MongoDB**. This mini-project demonstrates **CRUD operations** for a chat system where users can send, edit, and delete messages.

---

## � Features

- ✅ Add new chat messages  
- ✅ View all stored chat messages  
- ✅ Edit and update existing messages  
- ✅ Delete messages from the database  
- ✅ Uses **EJS** for templating  

---

## 📌 Tech Stack

- **Backend**: Node.js, Express.js  
- **Database**: MongoDB with Mongoose  
- **Templating Engine**: EJS  
- **Middleware**: Method-Override for PUT and DELETE requests  

---

## 🛠 Installation & Setup

### 📌 Prerequisites
- **Node.js** (v14 or higher)
- **MongoDB** (local or Atlas account)
- **Git**

### 🔹 Clone the Repository
```bash
git clone https://github.com/Udayan-Mal/express-mongo-mini-chat-app.git
cd express-mongo-mini-chat-app

🔹 Install Dependencies

npm install
🔹 Start MongoDB Locally
Ensure MongoDB is installed and running:

mongod --dbpath /path/to/your/mongodb/data
🔹 Run the Application


node index.js
The server will start at http://localhost:8080.

📌 Usage
🔹 User Actions
View all chats: http://localhost:8080/chats

Add a new chat: http://localhost:8080/chats/new

Edit a chat: http://localhost:8080/chats/:id/edit

Delete a chat: Uses a DELETE request

📂 Project Structure

express-mongo-mini-chat-app/
├── models/              # Mongoose schema for messages
├── routes/              # Express routes
├── views/               # EJS templates for frontend
├── public/              # Static assets (CSS, JS)
├── index.js             # Main server file
├── package.json         # Dependencies and scripts
└── README.md            # Project documentation
🔗 API Endpoints
Method	Endpoint	Description
GET	/chats	Fetch all chat messages
POST	/chats	Add a new message
GET	/chats/:id/edit	Fetch a single message for editing
PUT	/chats/:id	Update an existing message
DELETE	/chats/:id	Delete a message
🚀 Deployment Guide
The easiest way to deploy is using Render or Vercel:

🔹 Push to GitHub

git add .
git commit -m "Initial commit"
git push origin main
🔹 Deploy on Render
Go to Render.

Select New Web Service.

Connect your GitHub repo.

Add MongoDB URI in environment variables.

Click Deploy!

🤝 Contributing
Contributions are welcome! Follow these steps:

Fork the repository.

Create a branch (git checkout -b feature/your-feature).

Commit changes (git commit -m "Add feature").

Push the branch (git push origin feature/your-feature).

Open a Pull Request.

## 📜 License
This project is licensed under the **MIT License**. See the **LICENSE** file for details.

## 📧 Contact
For any questions or feedback, reach out to:
- **Udayan Mal**
- **GitHub**: [Udayan-Mal](https://github.com/Udayan-Mal)

Feel free to modify any sections as needed!