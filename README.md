# Car Rental Management System

A full-stack web application developed to simplify and manage car rental operations. The system allows customers to browse vehicles, submit rental requests, and manage their rentals, while administrators manage vehicles, users, and rental activities.

## Overview

The Car Rental Management System provides a centralized platform for managing vehicle rental services. It is built with React and TypeScript for the frontend and Django REST Framework for the backend.

## Features

**Customer**
- User registration and login.
- Browse available vehicles.
- View vehicle details and categories.
- Submit rental requests.
- Manage personal information.
- View rental history and status.

**Administrator**
- Dashboard for monitoring rental activities.
- Manage vehicles and categories.
- Manage registered users.
- View and manage rental requests.
- Track vehicle availability.
- Process vehicle returns.

**Security**
- JWT-based authentication.
- Role-based access control.
- Protected application routes.
- Secure API communication.

## Technologies

**Frontend:** React, TypeScript, Vite, Tailwind CSS

**Backend:** Python, Django, Django REST Framework

**Database:** MySQL

**Authentication:** JSON Web Tokens (JWT)

**Tools:** Git, GitHub, Axios

## Project Structure

```text
Car-Rental-Management-System/
│
├── Client/
│   ├── public/
│   ├── src/
│   │   ├── api/
│   │   ├── auth/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── schema/
│   │   └── types/
│   └── package.json
│
├── server/
│   ├── account/
│   ├── catalog/
│   ├── rental/
│   ├── adminpanel/
│   ├── server/
│   └── manage.py
│
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/amenlol/Car-Rental-Management-System.git

cd Car-Rental-Management-System
```

### 2. Backend Setup

```bash
cd server

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt
```

Configure your database and environment variables, then run:

```bash
python manage.py migrate

python manage.py runserver
```

### 3. Frontend Setup

Open another terminal:

```bash
cd Client

npm install

npm run dev
```

Frontend: `http://localhost:5173`

Backend: `http://127.0.0.1:8000`

## API Modules

| Module | Endpoint | Purpose |
|---|---|---|
| Authentication | `/api/auth/` | User authentication and management |
| Catalog | `/api/catalog/` | Vehicle and category management |
| Rental | `/api/rental/` | Rental operations |
| Admin Panel | `/api/adminpanel/` | Administrative dashboard |

## Project Purpose

The project aims to provide an efficient and user-friendly solution for managing car rental services, reducing manual administrative work, and improving vehicle and rental management.

## License

Copyright © 2025 Ebisa Getachew. All rights reserved.
