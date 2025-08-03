# MERN Stack Template

## Project Structure
```
mern-app/
├── client/               # React frontend
│   ├── src/
│   │   ├── components/  # Reusable components
│   │   ├── pages/      # Page components
│   │   ├── hooks/      # Custom hooks
│   │   ├── services/   # API services
│   │   └── utils/      # Utility functions
│   └── package.json
├── server/              # Express backend
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│   └── package.json
└── docker-compose.yml   # Docker configuration
```

## Features
- MongoDB with Mongoose
- Express.js REST API
- React with TypeScript
- Node.js backend
- Docker containerization
- JWT Authentication
- API Documentation
- Unit Testing Setup

## Getting Started

1. Clone this template
2. Install dependencies:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```
3. Set up environment variables
4. Start development servers:
   ```bash
   # Start backend
   cd server && npm run dev
   
   # Start frontend
   cd client && npm start
   ```
