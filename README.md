# Spotify Clone - Real-Time Music Streaming Application 🎵

A full-stack real-time music streaming application inspired by Spotify, built with the MERN stack (MongoDB, Express, React, Node.js). This application offers seamless track navigation, volume control, real-time chat, and user status updates to enhance the streaming experience.

---

## Features 🚀

- **Real-Time Music Streaming**: Stream tracks smoothly with precise controls for playback and volume adjustment.
- **Admin Dashboard**: Manage albums and songs with an intuitive interface for efficient content control.
- **Real-Time User Interaction**: Chat with other users and view their online/offline statuses and current listening activities.
- **User Analytics**: Aggregates interaction data to provide insights for improved user engagement.

---

## File Structure 📂

## Backend (Node.js + Express)
-/models: Defines MongoDB schemas for users, albums, and songs.
-/routes: Contains API routes for user authentication, music data, and chat.
-/controllers: Implements business logic for routes.
-server.js: Entry point for the backend, sets up Express and connects to MongoDB.

## Frontend (React)
-/src/components: Contains reusable components like Player, Dashboard, and Chat.
-/src/pages: Includes main pages such as Home, Admin, and Library.
-/src/utils: Utility functions for API calls and state management.
-App.js: Sets up routing and the main layout for the application.
-index.js: Entry point for rendering the React application.

---

## Technologies Used 💻

-**Frontend**: React, Redux, CSS Modules
-**Backend**: Node.js, Express
-**Database**: MongoDB
-**Real-Time Features**: WebSockets (Socket.IO)

