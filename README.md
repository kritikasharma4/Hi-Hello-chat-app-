📚 Hi-Hello Chat App
Hi-Hello Chat App is a real-time chat application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It enables users to chat seamlessly with real-time updates, media sharing, and secure authentication.

🚀 Features
✅ User Authentication (JWT & Google OAuth)
✅ Real-time Messaging with Socket.io
✅ Store and Retrieve Conversations from MongoDB
✅ Cloudinary Integration for Media Uploads
✅ User Profile Management
✅ Responsive UI with amazing Color Palette
✅ Logout Functionality Using MERN Authentication Setup


🛠️ Tech Stack
🌐 Frontend:
React.js

Axios

CSS / Material-UI (Optional)

🔥 Backend:
Node.js

Express.js

MongoDB

JWT Authentication

Socket.io (Real-Time Communication)

Cloudinary (Media Uploads)



🔧 Installation and Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/Hi-Hello-chat-app.git
cd Hi-Hello-chat-app
⚙️ Backend Setup
2. Configure Environment Variables
Create a .env file in the backend directory and add the following:

plaintext
Copy
Edit
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
3. Install Dependencies
bash
Copy
Edit
cd backend
npm install
4. Run the Backend
bash
Copy
Edit
npm run dev
Backend will run on http://localhost:5000

🎨 Frontend Setup
5. Install Dependencies
bash
Copy
Edit
cd frontend
npm install
6. Run the Frontend
bash
Copy
Edit
npm start
Frontend will run on http://localhost:3000

⚡️ API Endpoints
Auth Routes
POST /api/auth/register – Register a new user

POST /api/auth/login – Login user

Chat Routes
POST /api/chat – Create or access a chat

GET /api/chat – Get all chats

Message Routes
POST /api/message – Send a new message

GET /api/message/:chatId – Get all messages in a chat

🌐 Deployment Instructions
1. Build the Frontend
bash
Copy
Edit
cd frontend
npm run build
2. Deploy Backend
Deploy the backend to Render/Heroku/VPS.

Ensure correct environment variables are set in production.

3. Deploy Frontend
Deploy the frontend using Vercel/Netlify.

🧩 Troubleshooting
Make sure MongoDB is running or the connection string is correct.

Check that Cloudinary credentials are properly configured in .env.

Restart the server if environment variables are modified.

🤝 Contributing
Contributions are welcome!
To contribute:

Fork the repository.

Create a feature branch (git checkout -b feature-name).

Commit your changes (git commit -m 'Add feature').

Push to your branch (git push origin feature-name).

Open a Pull Request.

📄 License
This project is licensed under the MIT License.

📬 Contact
If you have any questions, feel free to reach out:
✉️ your-sharmakritika247k@gmail.com
🔗 GitHub: https://github.com/kritikasharma4

