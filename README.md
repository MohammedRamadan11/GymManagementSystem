# 🏋️ Gym Management System

<div align="center">

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

</div>

## 📋 Overview

A full-featured **Gym Management System** built with ASP.NET Core following a clean **3-Layer Architecture** (BLL, DAL, PL). The system handles all gym operations from member registration to subscription management.

---

## ✨ Features

- 👤 **Member Management** - Register, update, and manage gym members
- 💳 **Subscription Tracking** - Track membership plans and expiry dates
- 🏃 **Attendance Management** - Record and monitor member attendance
- 💰 **Payment Processing** - Handle membership payments and history
- 🔐 **Authentication & Authorization** - Secure login with role-based access
- 📊 **Dashboard** - Overview of gym statistics and reports

---

## 🏗️ Architecture

GymManagementSystem/ ├── GymManagementBLL/ # Business Logic Layer ├── GymManagementDAL/ # Data Access Layer └── GymManagementPL/ # Presentation Layer
---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| ASP.NET Core | Backend Framework |
| Entity Framework Core | ORM & Database Management |
| SQL Server | Database |
| C# | Programming Language |
| LINQ | Data Querying |
| JWT | Authentication |

---

## 🚀 Getting Started

### Prerequisites
- .NET 8 SDK
- SQL Server
- Visual Studio 2022

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/MohammedRamadan11/GymManagementSystem.git
"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=GymDB;Trusted_Connection=True;"
}
dotnet ef database update
dotnet run

