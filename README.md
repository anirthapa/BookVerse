# 📚 BookVerse

A book management platform built with React and .NET for discovering and organizing your favorite books.

## 🚀 Features

- User authentication (Login/Register)
- Browse and search books
- Personal bookshelf
- Add reviews and ratings
- Track reading progress

## 🛠️ Tech Stack

**Frontend:** React, React Router, Axios, Tailwind CSS  
**Backend:** .NET Core, Entity Framework, SQL Server  

## 📋 Prerequisites

- Node.js (v16+)
- .NET SDK (v6.0+)
- SQL Server

## ⚙️ Setup

### Frontend
```bash
cd frontend
npm install
npm start
```
Runs on `http://localhost:3000`

### Backend
```bash
cd backend
dotnet restore
dotnet ef database update
dotnet run
```
Runs on `http://localhost:5000`

## 📁 Project Structure
```
bookverse/
├── frontend/          # React application
└── backend/           # .NET API
```

## 🔧 Configuration

**Frontend (.env)**
```env
REACT_APP_API_URL=http://localhost:5000/api
```

**Backend (appsettings.json)**
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=BookVerseDB;..."
  }
}
```

## 📝 License

MIT License


---

⭐ Give this project a star if you like it!
