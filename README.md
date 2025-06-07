Project Management System (MERN Stack)
A project management application built using the MERN stack: MongoDB, Express.js, React.js, and Node.js.

🔧 Setup Instructions
Step 1: Install Dependencies
Navigate to the backend directory:

bash
Copy
Edit
cd backend
npm install
Navigate to the frontend directory:

bash
Copy
Edit
cd frontend
npm install
Step 2: Configure Environment Variables
In the backend directory, create a .env file and add:

ini
Copy
Edit
MONGODB_PATH=your-mongodb-connection-url
Step 3: Optional Server Config
You can customize the server port and CORS origin by adding the following to your .env:

ini
Copy
Edit
SERVER_PORT=your-port
CORS_ORIGIN=your-client-origin
Step 4: Run the Project
Start the backend server:

bash
Copy
Edit
npm run serve
Start the frontend application:

bash
Copy
Edit
npm start
📦 Packages Used
Frontend:

React

React Router

Axios

TailwindCSS

Headless UI

UUID

Backend:

Express.js

MongoDB

Joi

Cors

Dotenv

📜 Available Scripts (Frontend)
In the frontend directory, you can use the following:

npm start
Runs the app in development mode at http://localhost:3000

npm test
Runs the test runner in watch mode.

npm run build
Builds the app for production.

📝 Notes
Backend runs on port 9000 by default.

Frontend runs on port 3000 by default.

Ensure MongoDB is running locally or provide a cloud-based connection string.
