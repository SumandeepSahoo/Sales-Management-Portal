# 🧾 Sales Management Portal

A web-based portal built using ASP.NET Web Forms that enables role-based access and operations for Admins, Managers, and Sales Executives to manage clients, opportunities, proposals, and projects.

## 📌 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Setup Instructions](#setup-instructions)
- [Usage Guide](#usage-guide)
- [Contributing](#contributing)
  
---

## ✅ Features

- 🔐 Role-based Login System (Admin, Manager, Sales)
- 👥 Admin can create Managers and Salespersons
- 📈 Managers can manage announcements and sales teams
- 📊 Salespersons can manage:
  - Projects
  - Opportunities
  - Proposals
- 📬 Comment and feedback system

---

## 🛠️ Tech Stack
```
| Layer        | Technology           |
|--------------|----------------------|
| Frontend     | HTML, CSS, Bootstrap |
| Backend      | ASP.NET Web Forms (C#) |
| Client Logic | JavaScript           |
| Master Pages | ASP.NET Master Pages |
| Config       | web.config            |
```
---

## 📁 Folder Structure
```
Sales Management Portal/
├── AdminLogin/ # Admin UI Screens
├── ManagerLogin/ # Manager UI Screens
├── SalesLogin/ # Salesperson UI Screens
├── Content/ # CSS and Bootstrap styles
├── Scripts/ # JS scripts and form validations
├── *.aspx / *.aspx.cs # Main Web Forms and their code-behind
├── MainMaster.master # Shared layout (Master Page)
├── web.config # App settings and routing
```
---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```
   git clone https://github.com/SumandeepSahoo/sales-management-portal.git
   cd sales-management-portal
   ```
2. **Open in Visual Studio**
    ```
    Open the .sln or the folder directly in Visual Studio (preferably 2015 or later).
    ```
3. **Build and Run**
    ```
    Ensure .NET Framework is installed (e.g., 4.5+)
    Press F5 to build and run the project.
    ```
4. **Database Setup**
    ```
    The web.config may contain a connection string (not included here).
    Set up your SQL Server instance and update the connection string accordingly.
    ```
---

## 📘 Usage Guide

Navigate to Login.aspx to start.
Log in with respective role credentials (to be configured in the database).
Use the navigation system (handled by the MainMaster.master) to access modules based on role.

---

## 🤝 Contributing

-Contributions are welcome! Feel free to open issues or submit pull requests.
-Fork the repo
-Create a new branch (feature/your-feature)
-Commit your changes
-Push to the branch
-Open a pull request

---


