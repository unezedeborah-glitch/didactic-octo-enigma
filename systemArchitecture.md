# System Architecture – DoktorConnect

## Overview
Modular client-server architecture for scalability and maintainability.

## Frontend
- React.js + TailwindCSS
- Handles UI and API requests
- Uses JWT for authenticated sessions

## Backend
- Node.js + Express
- Business logic, authentication, API endpoints

## Database
- MongoDB Atlas
- Stores users, records, consultations securely

## Communication Flow
1. User interacts with frontend
2. Frontend calls backend APIs
3. Backend processes data & queries database
4. Response sent back to frontend

## Security
- HTTPS and JWT authentication
- Role-based access control

## Deployment
- Frontend: Vercel
- Backend: Render
- Database: MongoDB Atlas
