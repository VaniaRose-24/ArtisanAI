````
# 🎨 Artisan AI: The Creator's Collective

## Overview

Artisan AI is a full-stack web application designed for independent **creators and artisans**. It provides a platform for secure user authentication, portfolio management, and will eventually integrate specialized AI tools to assist in the creative process and digital asset generation.

This repository contains the complete source code for both the **React frontend** and the **Node/Express backend**.

---

## 🛠️ Tech Stack

### Frontend (Client)
* **React:** Frontend library for building the user interface.
* **React Router:** For navigation and client-side routing.
* **Firebase Client SDK:** For secure user authentication (Log In/Log Out).
* **Axios:** For making HTTP requests to the backend.
* **Aesthetic:** Minimalist design with an earthy, heritage color palette.

### Backend (Server)
* **Node.js & Express:** The runtime environment and framework for the REST API.
* **Firebase Admin SDK:** For privileged operations (e.g., user registration).
* **CORS:** Middleware for handling cross-origin communication.

---

## 💻 Getting Started

Follow these steps to get the project running on your local machine.

### 1. Prerequisites

* Node.js (LTS recommended)
* A Firebase Project with **Email/Password** sign-in enabled.

### 2. Backend Setup

1.  Navigate to the `server` directory and install dependencies:
    ```bash
    cd server
    npm install
    ```
2.  Place your Firebase Admin SDK **`serviceAccountKey.json`** file inside the `server` directory.
3.  Start the backend server:
    ```bash
    node server.js
    ```

### 3. Frontend Setup

1.  Navigate to the `client` directory and install dependencies:
    ```bash
    cd ../client
    npm install
    ```
2.  Ensure your **`client/src/firebase.js`** file contains your unique **Web App API Keys**.
3.  Start the frontend development server:
    ```bash
    npm start
    ```

The application runs on **`http://localhost:3000`** and is configured with a **proxy** for seamless API communication.

---

## 🚀 Project Progress and Roadmap

- **Foundation & Auth:** Complete, featuring Full Stack Setup, **Working Sign Up/Log In**, Minimal Artisan UI, and **Network Fixes**.
- **State Management:** In Progress (Auth Context Provider Setup is done).
- **Next Immediate Goal:** Implement **Protected Routes** and the **Dashboard** component.
- **Future Goal (Data & AI):** Integrate Firestore Database and Connect to the AI API Endpoint.
````
