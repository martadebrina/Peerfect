# Peerfect

Peerfect is a real-time peer-to-peer tutoring platform where students can request or provide help and exchange points instead of money.

## Overview

Peerfect allows students to:
- Create tutoring requests with course, topic, and description  
- Browse and accept requests from other users  
- Join live tutoring sessions  
- Earn and spend points within the platform  

## Tech Stack

Frontend:
- React (Vite)
- TypeScript
- Tailwind CSS

Backend:
- FastAPI (Python)
- MongoDB

Authentication:
- Auth0 (JWT-based)

Other:
- Jitsi (video sessions)
- Vercel (frontend deployment)
- Render (backend deployment)

## System Design

- Requests and user data are stored in MongoDB  
- FastAPI handles API endpoints and business logic  
- Auth0 manages authentication and secure access  
- Real-time updates are implemented using Server-Sent Events (SSE)  

## Challenges

- Integrating FastAPI with MongoDB and Auth0  
- Handling authentication flow between frontend and backend  
- Managing CORS issues  
- Preventing users from accepting their own requests  
