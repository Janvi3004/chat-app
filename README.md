<h1 align="center"> Fullstack Chat & Video Calling App </h1>
Highlights:

-  Real-time messaging with typing indicators, online/offline status, and emoji reactions  
-  Supports one-on-one and group video calls, including screen sharing and recording  
-  Implements JWT authentication with protected routes for secure access  
-  Features a language exchange platform offering 32 unique UI themes  
-  Built with React, Express, MongoDB, TailwindCSS, and TanStack Query  
-  Utilizes Zustand for efficient global state management  
-  Comprehensive error handling on both frontend and backend  
-  Prepared for free deployment with scalable architecture  
-  Integrates Stream API to deliver reliable chat and video functionalities  
-  Includes various additional features enhancing user experience

---

## 🧪 .env Setup

### Backend (`/backend`)

```
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend (`/frontend`)

```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
