# 📚 Library Inventory System

A simple yet powerful **Library Inventory System** built using **ASP.NET Core Web API**, designed to manage books, authors, categories, and inventory efficiently. Developed as part of the **CodTech .NET Internship**.


## 🚀 Features

- 📖 Add, Update, Delete, and View Books
- 👤 Manage Authors & Categories
- 🧾 Track Inventory & Book Status
- 🔍 Search and Filter Books
- 📡 RESTful API with JSON responses


## 🛠️ Technologies Used

| Tool / Framework      | Description                         |
|-----------------------|-------------------------------------|
| ASP.NET Core Web API  | Backend Framework                   |
| Entity Framework Core | ORM for Database Interaction        |
| SQL Server            | Relational Database                 |
| Swagger / Postman     | API Testing and Documentation       |
| C#                    | Backend Programming Language        |

---

## 📂 Project Structure
LibraryInventorySystem/
│
├── Controllers/ # API Controllers
├── Models/ # Data Models
├── Data/ # Database Context
├── Migrations/ # EF Core Migrations
├── DTOs/ # Data Transfer Objects
├── Program.cs # Main App Entry Point
└── appsettings.json # Configuration File

Sample APIs
GET /api/books – All Books

GET /api/books/{id} – Book by ID

POST /api/books – Add Book

PUT /api/books/{id} – Update Book

DELETE /api/books/{id} – Delete Book
