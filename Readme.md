Real-Time Chat Application
A real-time chat application built with modern web technologies, allowing users to exchange messages instantly. This application features user authentication, live messaging, and a responsive design to ensure seamless communication across devices.
Features
- Real-Time Messaging: Instant message delivery using WebSockets.
- User Authentication: Secure login and signup with password hashing.
- Chat Rooms: Create or join chat rooms for group conversations.
- Typing Indicators: See when someone is typing a message.
- Message Timestamps: Keep track of when messages were sent.
Tech Stack
- Frontend: React.js , TailwindCSS (or Bootstrap) for styling
- Backend: Node.js with Express.js, WebSocket or Socket.IO for real-time communication
- Database: MongoDB  for storing user data and chat history
- Authentication: JSON Web Tokens (JWT), bcrypt for password hashing
- Hosting: Deployed on [Heroku/Vercel/AWS/etc.]
Screenshots
https://www.imghippo.com/i/VJ5985oKI.png
https://www.imghippo.com/i/wnNr8019XCU.png
https://www.imghippo.com/i/OeoH9854Xm.png


Getting Started
Prerequisites
- Node.js (version 14 or higher)
- MongoDB or a hosted database (e.g., MongoDB Atlas)
Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Shriyam_802/realtime-chat-app.git
   cd Communication Main
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Set up your `.env` file:
   Create a `.env` file in the root directory and add the following:
   ```env
   PORT=3000
   MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/databaseName
   JWT_SECRET=secret
   
   ```![Screenshot (2)](https://github.com/user-attachments/assets/780e0c48-16d4-4ba0-b0f9-aa9c67c9c5c9)

4. Run the application:
   ```
   npm start
   ```
Usage
1. Visit `http://localhost:3000` in your browser.
2. Sign up or log in to your account.
3. Start a new chat or join an existing one.
Deployment
- Use Heroku, AWS, or any cloud platform to deploy the backend.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For any inquiries, reach out to  cseshriyam80