# 🎓 UniNotify

> **A smart faculty attendance & student feedback management system built for the Nitte University community.**

![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-MVC-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

---

## 📌 Overview

**UniNotify** is an ASP.NET Core MVC-based management system exclusively designed for the **Nitte University** community. It streamlines faculty attendance tracking and student feedback submissions while providing real-time faculty availability updates. Secure domain-restricted authentication and role-based dashboards ensure smooth communication between students, faculty, and administrators.

---

## ✨ Features

### 👨‍🎓 Students
- View **real-time faculty availability** before visiting departments
- Submit **structured feedback** for faculty
- Access personalized **student dashboard**

### 👨‍🏫 Faculty
- Mark and manage **daily attendance**
- View submitted **student feedback**
- Update **availability status** in real time

### 🛠️ Administrators
- **Monitor faculty attendance** across departments
- Manage **user accounts** and roles
- Access comprehensive **reports and analytics**

---

## 🔐 Authentication & Security

- **Domain-restricted login** — only `@nitte.edu.in` email addresses allowed
- **Role-based access control** — Student, Faculty, and Admin roles
- ASP.NET Core **Identity** for secure session management
- Protection against **CSRF, XSS, and SQL Injection**

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | ASP.NET Core MVC (.NET 8) |
| Language | C# |
| Database | Microsoft SQL Server |
| ORM | Entity Framework Core |
| Frontend | Razor Views, Bootstrap 5 |
| Auth | ASP.NET Core Identity |
| Real-time | SignalR (availability updates) |

---

## 📁 Project Structure

```
UniNotify/
├── Controllers/
│   ├── AccountController.cs
│   ├── AdminController.cs
│   ├── FacultyController.cs
│   └── StudentController.cs
├── Models/
│   ├── ApplicationUser.cs
│   ├── Attendance.cs
│   └── Feedback.cs
├── Views/
│   ├── Admin/
│   ├── Faculty/
│   ├── Student/
│   └── Shared/
├── Data/
│   └── ApplicationDbContext.cs
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── images/
├── appsettings.json
└── Program.cs
```

---

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or VS Code


## 🔧 Configuration

| Setting | Description |
|---|---|
| `AllowedDomain` | Set to `nitte.edu.in` for domain restriction |
| `ConnectionStrings` | SQL Server connection string |
| `JWT:Secret` | Secret key for token signing |

---


## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---


## 🏫 Developed for

**Nitte (Deemed to be University)** — Mangaluru, Karnataka, India

---

> _"Connecting the Nitte community — one click at a time."_
