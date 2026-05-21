# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

```
octofit-tracker/
├── frontend/          # React 19 + Vite (Port 5173)
└── backend/           # Node.js + Express + TypeScript (Port 8000)
```

## Ports

- **Frontend**: 5173
- **Backend API**: 8000
- **MongoDB**: 27017

## Getting Started

### Prerequisites

- Node.js 18+
- MongoDB running locally or connection string configured

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

Backend API will be available at `http://localhost:8000`

### MongoDB Setup

Ensure MongoDB is running on port 27017:

```bash
# If using Docker
docker run -d -p 27017:27017 --name mongodb mongo:latest

# Or start MongoDB locally
mongod
```

## Development

- Frontend: React 19 with Vite for fast development and building
- Backend: Express.js with TypeScript for type safety and REST APIs
- Database: MongoDB with Mongoose for data modeling and access

## API Documentation

### Health Check
- `GET /api/health` - Check if API is running

More endpoints to be added...
