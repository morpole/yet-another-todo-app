# Standard todo app 
Created using node and mongoDB
## Deployed on render.com @ https://todo-app-n035.onrender.com/
<img src="./public/images/screenshot.jpeg" alt="screenshot" style="height:400px;">
# Yet Another Todo App

A robust todo application built with Node.js, Express, and MongoDB. This project provides a web-based interface to manage tasks, including creation, editing, deletion, and completion tracking, with data persisted in a MongoDB Atlas database. The frontend uses HTML, Tailwind CSS, and vanilla JavaScript for a responsive and user-friendly experience, complemented by unit tests using Vitest.

## Features
- **Task Management**: Add, edit, delete, and mark tasks as complete.
- **Persistent Storage**: Tasks are stored in MongoDB Atlas for reliable data persistence.
- **Responsive UI**: Built with Tailwind CSS and custom styles for desktop and mobile compatibility.
- **Real-time Updates**: Tasks reload dynamically after CRUD operations.
- **Unit Testing**: Includes tests for task API endpoints using Vitest.

## Prerequisites
- Node.js (v16+ recommended) and npm installed.
- A MongoDB Atlas account with a connection URI (stored in a `.env` file).
- Git installed to clone this repository.
- A code editor (e.g., VS Code).

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/morpole/yet-another-todo-app.git
   cd yet-another-todo-app
  
## Install Dependencies

2. **Run**:
   ```bash
   npm install

## Configure Environment

3. **Create a .env file in the root directory with your MongoDB Atlas URI**:
   ```bash
   MONGO_URI=your_mongodb_atlas_connection_string
   PORT=3000
Replace your_mongodb_atlas_connection_string with your actual MongoDB URI from Atlas.

4. **Run the Application**:
   ```bash
   npm start
Open http://localhost:3000 in your browser to use the app.


