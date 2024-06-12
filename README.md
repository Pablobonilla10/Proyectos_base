
# Task Manager Project

This is a full-stack task manager application with a React frontend and a Node.js/Express backend. The project uses MongoDB for data storage.

## Project Structure

```
task-manager/
  ├── backend/        # Backend server with Node.js and Express
  └── frontend/       # Frontend application with React
  └── README.md       # Project documentation
```

## Installation and Setup

### Backend

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory and add your MongoDB connection string and JWT secret:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Start the frontend application:
   ```bash
   npm start
   ```

## Features

- User registration and authentication
- Create, read, update, and delete tasks
- Protected routes and JWT-based authentication

## Technologies Used

- Frontend: React
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT

## License

This project is licensed under the MIT License.
