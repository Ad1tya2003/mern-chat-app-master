# MERN Stack Project: Build and Deploy a Real Time Chat App | JWT, Socket.io


MERN Real-Time Chat App

This project is a real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with additional features like real-time messaging via Socket.io, authentication and authorization with JWT, and a modern UI styled with TailwindCSS and DaisyUI.
Features

    Tech Stack: MERN + Socket.io + TailwindCSS + Daisy UI.
    Authentication & Authorization: Secured with JWT.
    Real-Time Messaging: Powered by Socket.io.
    Online User Status: Shows real-time online/offline status using Socket.io and React Context.
    Global State Management: Managed with Zustand.
    Error Handling: Robust error handling on both the client and server.
    Responsive UI: Modern and responsive design with TailwindCSS and DaisyUI components.
    Deployment: Guide for deploying the app like a pro, for free.

Tech Stack

    MongoDB: Database for storing user information, messages, and authentication data.
    Express: Backend framework for handling API requests.
    React: Frontend framework for building the user interface.
    Node.js: Runtime environment for building the backend server.
    Socket.io: Real-time communication between clients and the server.
    JWT: For secure authentication and authorization.

Setup Instructions
1. Clone the Repository

```bash

git clone https://github.com/your-repo/mern-chat-app.git
cd mern-chat-app
```
2. Install Dependencies

For both the server and client, you need to install the necessary dependencies.
Server

```bash

cd server
npm install
```
Client
```
bash

cd client
npm install
```
3. Environment Variables

Create a .env file in the server folder and set the following environment variables:
```
bash

PORT=your_port
MONGO_DB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```
4. Run the App
Build the Client
```
bash

npm run build
```
Start the Server
```
bash

npm start
```
5. Real-Time Messaging

This app uses Socket.io to handle real-time messaging. It also maintains online user status using Socket.io and React Context for an enhanced user experience.
6. Global State Management

The app utilizes Zustand for global state management, ensuring a seamless and scalable architecture.
7. Deployment

This app can be deployed easily using services like Heroku, Vercel, or any cloud provider. Follow deployment best practices to scale and run the app in production environments.
