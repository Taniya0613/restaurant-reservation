# Restaurant Reservation System

A full-stack MERN application for restaurant reservations with a modern UI.

## Features

- User-friendly reservation form
- Real-time form validation
- MongoDB database integration
- Responsive design
- Modern UI with animations

## Tech Stack

- Frontend: React.js, React Router, Axios, React Hot Toast
- Backend: Node.js, Express.js
- Database: MongoDB
- Styling: CSS3

## Live Demo

- Frontend: [https://restaurant-reservation-taniya.vercel.app](https://restaurant-reservation-taniya.vercel.app)
- Backend API: [https://restaurant-reservation-api.onrender.com](https://restaurant-reservation-api.onrender.com)

## Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- Git

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Taniya0613/restaurant-reservation.git
cd restaurant-reservation
```

2. Install backend dependencies:

```bash
cd backend
npm install
```

3. Install frontend dependencies:

```bash
cd frontend
npm install
```

4. Create a `.env` file in the backend directory with the following variables:

```
PORT=4000
FRONTEND_URL=http://localhost:5173
MONGO_URI=your_mongodb_connection_string
```

## Running the Application

1. Start the backend server:

```bash
cd backend
npm start
```

2. Start the frontend development server:

```bash
cd frontend
npm run dev
```

The application will be available at:

- Frontend: http://localhost:5173
- Backend: http://localhost:4000

## Deployment

This project is deployed using:

- Frontend: [Vercel](https://vercel.com)
- Backend: [Render](https://render.com)
- Database: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

## Environment Variables

### Frontend (.env)

```
VITE_API_URL=https://restaurant-reservation-api.onrender.com
```

### Backend (.env)

```
PORT=4000
FRONTEND_URL=https://restaurant-reservation-taniya.vercel.app
MONGO_URI=your_mongodb_connection_string
```

## License

MIT
