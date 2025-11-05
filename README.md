Real-Time Chat Application (MERN Stack)
📌 Overview

This is a Real-Time Chat Application built using the MERN stack (MongoDB, Express.js, React, Node.js) with Socket.IO for instant messaging.
Users can sign up, log in, and chat instantly with other users in real-time.
Authentication is handled with JWT, and user sessions are secured with cookies.

🚀 Tech Stack

Frontend: React.js, Tailwind CSS / CSS, Axios
Backend: Node.js, Express.js
Database: MongoDB (Mongoose ORM)
Real-Time Communication: Socket.IO
Authentication: JWT (JSON Web Token), bcrypt.js
Deployment: Render / Vercel / Netlify / MongoDB Atlas

⚙️ Features

✅ Real-time bi-directional chat using Socket.IO
✅ User authentication (Login & Register)
✅ Secure password hashing with bcrypt
✅ Online/offline user status tracking
✅ Chat history stored in MongoDB
✅ Responsive UI for all screen sizes
✅ Environment variable support using .env

🛠️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

2️⃣ Setup the backend
cd backend
npm install


Create a .env file in the backend folder and add:

PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret


Then start the backend:

npm run dev

3️⃣ Setup the frontend
cd ../frontend
npm install
npm run dev

⚡ Run the App

After starting both servers, open your browser and visit:

http://localhost:5173


or (depending on your frontend port)

📁 Folder Structure
RealTimeChat/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── package.json
│
└── README.md

🔐 Environment Variables
Variable	Description
PORT	Backend server port
MONGO_URI	MongoDB connection string
JWT_SECRET	Secret key for JWT authentication
🧠 Future Enhancements

💬 Group chats

📸 Image/file sharing

🔔 Push notifications

🧑‍🤝‍🧑 Typing indicators

🌐 Online presence tracking

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

🧾 License

This project is open-source under the MIT License
.

🧑‍💻 Author

[Your Name]
📧 [your.email@example.com
]
🌐 [your-portfolio-link-if-any]
🔗 [GitHub Profile Link]