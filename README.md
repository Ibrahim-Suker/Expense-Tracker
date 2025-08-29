💰 Expense Tracker
https://img.shields.io/badge/.NET-8.0-purple?logo=dotnet
https://img.shields.io/badge/ASP.NET_Core-MVC-blue?logo=dotnet
https://img.shields.io/badge/License-MIT-blue.svg
https://img.shields.io/badge/Status-Active-brightgreen.svg
https://img.shields.io/github/issues/Ibrahim-Suker/Expense-Tracker
https://img.shields.io/github/stars/Ibrahim-Suker/Expense-Tracker

A modern, feature-rich personal finance management system built with ASP.NET Core MVC. Track your income, expenses, and savings goals with beautiful visualizations and intuitive controls.

https://via.placeholder.com/800x400?text=Expense+Tracker+Dashboard+Preview

✨ Features
📊 Financial Management
Income & Expense Tracking - Record all financial transactions with ease

Category Management - Organize transactions with custom categories

Visual Dashboard - Interactive charts and financial summaries

Budget Goals - Set and monitor spending limits

🎨 User Experience
Responsive Design - Beautiful Bootstrap 5 interface that works on all devices

Dark/Light Mode - Choose your preferred theme

Intuitive UI - Clean, modern interface with smooth interactions

🔧 Technical Excellence
Entity Framework Core - Code-first approach with migrations

SQL Server Database - Robust data storage

Dependency Injection - Clean, maintainable architecture

RESTful Design - Well-structured API endpoints

🛠 Tech Stack
Backend: ASP.NET Core 8 MVC, C# 12, Entity Framework Core

Frontend: HTML5, CSS3, Bootstrap 5, JavaScript, Chart.js

Database: SQL Server with EF Core Migrations

Authentication: ASP.NET Core Identity (Optional)

Deployment: Docker-ready, Azure compatible

🚀 Getting Started
Prerequisites
.NET 8.0 SDK

SQL Server or SQL Server Express

Git

Installation
Clone the repository

bash
git clone https://github.com/Ibrahim-Suker/Expense-Tracker.git
cd Expense-Tracker
Configure the database

Update the connection string in appsettings.json:

json
"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=ExpenseTracker;Trusted_Connection=true;MultipleActiveResultSets=true"
}
Apply database migrations

bash
dotnet ef database update
Run the application

bash
dotnet run
Open your browser and navigate to https://localhost:5001

📖 Usage
Adding Transactions
Navigate to the Transactions section

Click Add New Transaction

Select transaction type (Income/Expense)

Choose a category, enter amount and description

Save to add to your financial records

Managing Categories
Go to Categories from the main menu

Create custom categories for better organization

Assign colors and icons for visual distinction

Viewing Reports
Check the Dashboard for financial overview

Use date filters to analyze specific periods

View category-wise spending breakdowns

Monitor budget progress with visual indicators

📊 API Endpoints
The application provides RESTful API endpoints for extended functionality:

Endpoint	Method	Description
/api/transactions	GET	Retrieve all transactions
/api/transactions/{id}	GET	Get specific transaction
/api/transactions	POST	Create new transaction
/api/categories	GET	List all categories
/api/reports/summary	GET	Get financial summary
🏗 Project Structure
text
Expense-Tracker/
├── Controllers/          # MVC Controllers
├── Models/              # Data models and ViewModels
├── Views/               # Razor views
├── Services/            # Business logic layer
├── Data/                # DbContext and migrations
├── wwwroot/             # Static files (CSS, JS, images)
├── appsettings.json     # Configuration
└── Program.cs           # Application entry point
🤝 Contributing
We love contributions! Here's how you can help:

Fork the project

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

Please read CONTRIBUTING.md for details on our code of conduct.

🐛 Issue Tracking
Found a bug or have a feature request? Open an issue and we'll address it promptly.

📦 Deployment
Local Deployment
bash
dotnet publish -c Release
Docker Deployment
bash
docker build -t expense-tracker .
docker run -p 5000:80 expense-tracker
Azure Deployment
https://aka.ms/deploytoazurebutton

🔮 Future Enhancements
Multi-currency support

Recurring transactions

Data export/import (CSV, Excel)

Mobile application

Bank synchronization

Advanced reporting

Investment tracking

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Bootstrap for the responsive UI components

Chart.js for beautiful data visualizations

Font Awesome for the excellent icon library

📬 Contact
Ibrahim Suker - ibrahimsukeroo@gmail.com

Project Link: https://github.com/Ibrahim-Suker/Expense-Tracker
