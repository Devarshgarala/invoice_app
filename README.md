**Screenshots of app**


**#Home page**

![image](https://github.com/user-attachments/assets/c563083b-faf2-4a53-995b-4d41921ac1fb)

**#Invoice page**

![image](https://github.com/user-attachments/assets/89daf4c6-fb4e-4e14-b5a6-05a219134899)

**#Adding new invoice**

![image](https://github.com/user-attachments/assets/80f1f2ac-7d58-4da8-8d0c-33ca0e33086d)

**#Adding details of invoice**

![image](https://github.com/user-attachments/assets/1ac4332c-e308-455f-a919-d38506ec53cc)

**#Partners page**

![image](https://github.com/user-attachments/assets/418ecaaa-9f70-4d55-a90a-216181e9ab94)

**#Adding new partner**

![image](https://github.com/user-attachments/assets/25ba512f-452e-45d6-b3f9-0bdc70a8b4b8)


**#Tried google auth page getting error**

![Screenshot 2025-01-19 124125](https://github.com/user-attachments/assets/cb8a0d4c-6838-451d-bc7f-09e23e2d4a3e)


**#And for zapier part I tried but it was paid only.**

![Screenshot (13)](https://github.com/user-attachments/assets/15f104a6-5f31-4377-8abe-6e32816850af)


**#MongoDB for backend**
![image](https://github.com/user-attachments/assets/f0fcad28-0bd5-4b5c-a140-c05180ab1907)


# Invoices App - MERN Stack

## Introduction

This repository contains the code for a MERN (MongoDB, Express.js, React, Node.js) stack application for managing invoices. The project is divided into two folders: `frontend` for the Vite/React frontend and `backend` for the MERN stack backend.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js and npm](https://nodejs.org/)
- [MongoDB Atlas Account](https://www.mongodb.com/)

### Clone the Repository

## Frontend Setup


Navigate to the frontend directory:

```bash
cd frontend
```

Create a .env file in the frontend directory and specify the API URL:

```bash
VITE_REACT_APP_API_URL=http://localhost:4000/api/
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

The frontend will be accessible at http://localhost:5174/

## Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Create a .env file in the backend directory and define the following:
```bash
PORT=4000
MONGO_URI=<Your MongoDB Connection String>
```

Replace <Your MongoDB Connection String> with your actual MongoDB connection string.

Install dependencies:
```bash
npm install
```

Run the development server:

```bash
npm run dev
```

The backend will be running at http://localhost:4000

Now, the Invoices App should be fully functional locally.

