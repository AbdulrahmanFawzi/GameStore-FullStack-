# 🎮 GameStore API

A full-stack Game Store application built with **ASP.NET Core Minimal API** for the backend and a frontend client. This project was created as part of my ASP.NET Core learning journey to practice building RESTful APIs using modern .NET technologies.

---

## 🚀 Features

- View all games
- Get a game by ID
- Create a new game
- Update an existing game
- Delete a game
- Manage game genres
- Data validation
- SQLite database
- Entity Framework Core
- Dependency Injection
- Async CRUD operations

---

## 🛠️ Tech Stack

### Backend
- ASP.NET Core 9 Minimal API
- Entity Framework Core
- SQLite
- Dependency Injection
- RESTful API
- Data Validation

### Frontend
- React
- TypeScript
- Vite

---

## Project Structure

### Backend (GameStore.Api)

```
GameStore.Api/
├── Data/                  # Database context and migrations
├── Dtos/                  # Data Transfer Objects
├── Endpoints/             # Minimal API endpoints
├── Models/                # Entity models (Game, Genre)
├── appsettings.json       # Configuration
└── Program.cs             # Application entry point
```

### Frontend (GameStore.React)

```
GameStore.React/
├── src/
│   ├── clients/           # API client services
│   ├── components/        # React components
│   ├── models/            # TypeScript interfaces
│   ├── pages/             # Page components
│   ├── App.tsx            # Main app component
│   └── main.tsx           # Application entry point
└── public/                # Static assets
```

## 📌 API Endpoints

### Games

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/games` | Get all games |
| GET | `/games/{id}` | Get game by ID |
| POST | `/games` | Create a new game |
| PUT | `/games/{id}` | Update a game |
| DELETE | `/games/{id}` | Delete a game |

### Genres

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/genres` | Get all genres |

---

## 🗄️ Database

This project uses **SQLite** with **Entity Framework Core**.

Main concepts used:

- DbContext
- DbSet
- Migrations
- Data Seeding

---

## 📖 What I Learned

Through this project I practiced:

- Building REST APIs
- CRUD operations
- Route Groups
- DTOs
- Model Validation
- Entity Framework Core
- SQLite Integration
- Database Migrations
- Dependency Injection
- Service Lifetimes
- Async Programming
- Clean project organization

---

## ▶️ Running the Project

### Backend

```bash
cd backend
dotnet restore
dotnet ef database update
dotnet run
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📷 Preview

_Add screenshots here._

---

## 👨‍💻 Author

**Abdulrahman Al-Luhaybi**

Software Engineering Graduate

Backend Developer (.NET)

GitHub:
