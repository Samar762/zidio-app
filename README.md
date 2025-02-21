# Zidio Task Management

A real-time task management application with Firebase integration.

## Setup Instructions

1. Clone the repository
2. Install dependencies: `npm install`
3. Copy .env.example to .env: `cp .env.example .env`
4. Add your Firebase credentials to the .env file
5. Start the development server: `npm start`

## Features

- Real-time task synchronization
- Drag-and-drop interface
- Secure authentication
- Role-based permissions
- Responsive design

## Configuration

Make sure to set up the following environment variables in your .env file:

- FIREBASE_API_KEY
- FIREBASE_AUTH_DOMAIN
- FIREBASE_DATABASE_URL
- FIREBASE_PROJECT_ID
- FIREBASE_STORAGE_BUCKET
- FIREBASE_MESSAGING_SENDER_ID
- FIREBASE_APP_ID

## Running the Application

```bash
npm start
```

The application will be available at http://localhost:8080
