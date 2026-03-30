# Local Connect E-commerce Platform

A Full-Stack E-commerce platform connecting local services and products.

## Introduction

Local Connect is a unified e-commerce web application designed to simplify access to local repair services and event ticket transactions through a single digital platform. The system allows users to conveniently book services such as AC repair, electrical, mechanical, and electronics maintenance.

In addition, the platform provides a secure marketplace for buying and reselling event tickets, helping users avoid losses from unused tickets before their expiration.

The application integrates Stripe for secure, reliable, and seamless payment processing. Key features include time-slot booking, cart-based scheduling, and an AI-powered chatbot that enhances customer support and overall user interaction.

Built using the MERN stack (MongoDB, Express.js, Node.js, and React.js), Local Connect combines a responsive user interface with efficient backend architecture to deliver a scalable, smooth, and user-friendly experience for both customers and service providers.

<img width="1919" height="918" alt="Screenshot 2025-04-28 002815" src="https://github.com/user-attachments/assets/cc5b9c4b-3030-4077-821e-d753dc365c40" />
<img width="1900" height="910" alt="Screenshot 2025-04-28 002846" src="https://github.com/user-attachments/assets/feb024c6-679a-4319-9efe-c4bae824829a" />
<img width="1919" height="914" alt="Screenshot 2025-04-28 003327" src="https://github.com/user-attachments/assets/e32e965a-47b8-4916-8c88-7345b246a08c" />


## Project Structure

```
Local-Connect-Ecommerce/
├── Frontend/          # React.js frontend application
├── Backend/           # Express.js API server
├── Stripe/           # Stripe payment processing server
└── README.md         # This file
```

## Development Setup

### 1. Frontend (React App)
```bash
cd Frontend
npm install
npm run dev
# Runs on http://localhost:5173
```

### 2. Backend (API Server)
```bash
cd Backend
npm install
npm start
# Runs on http://localhost:5003
```

### 3. Stripe (Payment Server)
```bash
cd Stripe
npm install
npm start
# Runs on http://localhost:5000
```

## Deployment on Render

Create 3 separate services:

### Frontend Service
- **Root Directory**: `Frontend`
- **Build Command**: `npm install; npm run build`
- **Start Command**: `npm run preview`

### Backend Service
- **Root Directory**: `Backend`
- **Build Command**: `npm install`
- **Start Command**: `npm start`

### Stripe Service
- **Root Directory**: `Stripe`
- **Build Command**: `npm install`
- **Start Command**: `npm start`

## Environment Variables

Each service has its own `.env` file with appropriate configurations.

## Technologies Used

- **Frontend**: React, Vite, React Router, Axios
- **Backend**: Express.js, MongoDB, MySQL, JWT, Multer
- **Payment**: Stripe API
- **Deployment**: Render
