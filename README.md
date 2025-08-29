# 💰 Expense Tracker

[![.NET](https://img.shields.io/badge/.NET-8.0-purple?logo=dotnet)](https://dotnet.microsoft.com/)
[![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-MVC-blue?logo=dotnet)](https://dotnet.microsoft.com/apps/aspnet)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/Ibrahim-Suker/Expense-Tracker)](https://github.com/Ibrahim-Suker/Expense-Tracker/issues)
[![GitHub Stars](https://img.shields.io/github/stars/Ibrahim-Suker/Expense-Tracker)](https://github.com/Ibrahim-Suker/Expense-Tracker/stargazers)

A modern, feature-rich personal finance management system built with **ASP.NET Core MVC**. Track your income, expenses, and savings goals with **beautiful visualizations and intuitive controls**.

![Expense Tracker Dashboard](https://via.placeholder.com/800x400?text=Expense+Tracker+Dashboard+Preview)

---

## ✨ Features

### 📊 Financial Management
- **Income & Expense Tracking** – Record all financial transactions with ease  
- **Category Management** – Organize transactions with custom categories  
- **Visual Dashboard** – Interactive charts and financial summaries  
- **Budget Goals** – Set and monitor spending limits  

### 🎨 User Experience
- **Responsive Design** – Built with Bootstrap 5 for all devices  
- **Dark/Light Mode** – Choose your preferred theme  
- **Intuitive UI** – Clean and modern interface with smooth interactions  

### 🔧 Technical Excellence
- **Entity Framework Core** – Code-first approach with migrations  
- **SQL Server** – Robust data storage  
- **Dependency Injection** – Clean and maintainable architecture  
- **RESTful API** – Well-structured endpoints for integration  

---

## 🛠 Tech Stack

- **Backend:** ASP.NET Core 8 MVC, C# 12, EF Core  
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript, Chart.js  
- **Database:** SQL Server with EF Core Migrations  
- **Authentication:** ASP.NET Core Identity *(Optional)*  
- **Deployment:** Docker-ready, Azure compatible  

---

## 🚀 Getting Started

### ✅ Prerequisites
- [.NET 8.0 SDK](https://dotnet.microsoft.com/download)  
- [SQL Server or SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)  
- [Git](https://git-scm.com/)  

### ⚡ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ibrahim-Suker/Expense-Tracker.git
   cd Expense-Tracker

Configure the database
Update the connection string in appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=ExpenseTracker;Trusted_Connection=true;MultipleActiveResultSets=true"
}


Apply database migrations

dotnet ef database update


Run the application

dotnet run


Open 👉 https://localhost:5001
📖 Usage
➕ Adding Transactions

Navigate to Transactions

Click Add New Transaction

Select Income/Expense, choose a category, enter amount & description

Save to record it

📂 Managing Categories

Navigate to Categories

Create custom categories with colors & icons

Organize transactions visually

📈 Viewing Reports

Dashboard shows financial overview & charts

Use filters to view data by date range or category

Monitor budget progress with indicators

📊 API Endpoints
Endpoint	Method	Description
/api/transactions	GET	Retrieve all transactions
/api/transactions/{id}	GET	Get a specific transaction
/api/transactions	POST	Create a new transaction
/api/categories	GET	List all categories
/api/reports/summary	GET	Get financial summary
🏗 Project Structure
Expense-Tracker/
├── Controllers/        # MVC Controllers
├── Models/             # Data models and ViewModels
├── Views/              # Razor views
├── Services/           # Business logic layer
├── Data/               # DbContext and migrations
├── wwwroot/            # Static files (CSS, JS, images)
├── appsettings.json    # Configuration
└── Program.cs          # Application entry point

🤝 Contributing

Contributions are welcome!

Fork the project

Create a feature branch

git checkout -b feature/AmazingFeature


Commit changes

git commit -m "Add some AmazingFeature"


Push to your branch

git push origin feature/AmazingFeature


Open a Pull Request

👉 Please read CONTRIBUTING.md for more details.

🐛 Issue Tracking

Found a bug 🐞? Have a feature request 💡?
Open an issue
 and we’ll address it promptly.

📦 Deployment
Local Deployment
dotnet publish -c Release

Docker
docker build -t expense-tracker .
docker run -p 5000:80 expense-tracker

Azure

🔮 Future Enhancements

🌍 Multi-currency support

🔁 Recurring transactions

📤 Data export/import (CSV, Excel)

📱 Mobile application

🏦 Bank synchronization

📊 Advanced reporting

📈 Investment tracking

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.

🙏 Acknowledgments

Bootstrap
 for responsive UI

Chart.js
 for data visualizations

Font Awesome
 for icons

📬 Contact

👤 Ibrahim Suker

Email: ibrahimsukeroo@gmail.com

GitHub: @Ibrahim-Suker

🔗 Project Link: Expense Tracker
