# QuickChat

A real-time chat application with user authentication, one-on-one messaging, and online status tracking.

## Features

- User signup and login with JWT authentication
- Real-time one-on-one messaging using Socket.IO
- Online/offline user status indicators
- Profile page with profile picture upload (via Cloudinary)
- Image sharing in chat
- Responsive UI

## Tech Stack

**Frontend:** React, Tailwind CSS, Vite, Socket.IO Client, React Router, Axios

**Backend:** Node.js, Express, MongoDB (Mongoose), Socket.IO, JWT, Cloudinary, bcryptjs

## Prerequisites

- Node.js
- MongoDB Atlas account (or local MongoDB)
- Cloudinary account

## Setup

### 1. Clone the repository

```bash
git clone <repo-url>
cd chat-app
```

### 2. Backend setup

```bash
cd server
npm install
```

Create a `.env` file in the `server` directory:

```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the server:

```bash
npm run start
```

### 3. Frontend setup

```bash
cd client
npm install
npm run dev
```

The app will be available at `http://localhost:5173`.
