# Uber Clone Web App

This project is a web version of the Uber mobile app, designed primarily for mobile screens. The UI is optimized for small screens and may not look as good on large desktop displays unless the browser window is minimized.

**Note:**  
The Google Maps API key is required for map functionality. Without a valid API key, map features will not work.

---

## Getting Started

### Prerequisites

You need to set up both the backend and frontend environments. Each has its own dependencies and environment variables.

---

## Packages Required

### Backend

Install these packages in the `Backend` directory:

- express
- mongoose
- dotenv
- cors
- cookie-parser
- bcrypt
- jsonwebtoken
- axios
- express-validator
- socket.io

You can install all dependencies using:

```sh
npm install
```

### Frontend

Install these packages in the `frontend` directory:

- react
- react-dom
- react-router-dom
- axios
- @gsap/react
- gsap
- @react-google-maps/api
- remixicon
- socket.io
- socket.io-client
- tailwindcss
- @tailwindcss/vite
- vite

You can install all dependencies using:

```sh
npm install
```

---

## Environment Variables

### Backend `.env` Example

Create a `.env` file in the `Backend` directory with the following variables:

```
PORT=your_port
DB_CONNECT=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_MAPS_API=your_google_maps_api_key
```

### Frontend `.env` Example

Create a `.env` file in the `frontend` directory with the following variables:

```
VITE_BASE_URL=your_backend_api_base_url
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

---

## Notes

- The UI is best experienced on mobile devices or minimized browser windows.
- Make sure to provide your own Google Maps API key for full map functionality.
- Do **not** commit your actual `.env` files or sensitive keys to version control.

---
