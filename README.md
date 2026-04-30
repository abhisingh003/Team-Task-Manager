# Team Task Manager

A production-ready task management web application built with Node.js, Express, MongoDB, Mongoose, JWT authentication, and EJS server-side rendering.

## Features

- User signup and login
- Role-based access control: admin and member
- Admin-only project creation and member management
- Task assignment and member status updates
- Dashboard with overdue highlights and task summaries

## Folder Structure

- `models/`
- `controllers/`
- `routes/`
- `middleware/`
- `views/`
- `public/css/`
- `app.js`

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```
2. Create `.env` from `.env.example`.
3. Start the server:
   ```bash
   npm start
   ```

## Deployment on Railway

1. Create a new Railway project and connect your GitHub repo or deploy from the folder.
2. Set environment variables: `PORT`, `MONGO_URI`, `JWT_SECRET`, `COOKIE_NAME`, `NODE_ENV`.
3. Use the start command: `npm start`.
