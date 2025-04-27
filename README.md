# Notes Web Application

[![Made with MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Made with Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Made with React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Made with Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Made with Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

A full-stack Notes application built with the MERN (MongoDB, Express, React, Node.js) stack. This application allows users to register, log in, and securely create, edit, delete, and manage notes.

## Screenshots


<p align="center">
  <img src="https://imgur.com/3R42Zkr.png" alt="Login page" width="900">
</p>
<p align="center">
  <img src="https://imgur.com/XVUZrnE.png" alt="Empty home page" width="900">
</p>
<p align="center">
  <img src="https://imgur.com/eMFsw15.png" alt="All notes page" width="900">
</p>
<p align="center">
  <img src="https://imgur.com/uUkHiz5.png" alt="Add/Edit note page" width="900">
</p>

## Tech Stack

- **Frontend**: React, Axios, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/ayushagupta/Notes-App.git
```

### 2. Setup backend

```bash
cd backend
npm install
```

Create a `config.json` file to store the database connection string as follows.

```json
{
  "connectionString": "<your-connection-string>"
}
```

Create a `.env` file to store the JWT secret to authenticate requests.

```
ACCESS_TOKEN_SECRET=<your-secret>
```

Start the backend server.

```bash
npm start
```

### 3. Setup frontend

```bash
cd frontend/notes-app
npm install
```

Start the React frontend.

```bash
npm run dev
```

Go to `http://localhost:5173/dashboard` in your browser.

## Future scope

* [ ] Categories and Labels to organize notes more efficiently
* [ ] LLM integration for summarization and/or question-answering
* [ ] Dark Mode toggle for better accessibility
* [ ] Multi-language Support
