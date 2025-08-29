# 💰 Expense Tracker

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![.NET](https://img.shields.io/badge/.NET-8.0-purple?logo=dotnet)](https://dotnet.microsoft.com/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/Ibrahim-Suker/Expense-Tracker)](https://github.com/Ibrahim-Suker/Expense-Tracker/issues)

> A simple and effective personal finance management system to track **income, expenses, and savings goals**.  
> Built with **C#, ASP.NET Core MVC, EF Core, and SQL** for a scalable and maintainable experience.

---

## 📌 Table of Contents
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [⚙️ Installation](#️-installation)
- [📖 Usage](#-usage)
- [📊 API Endpoints](#-api-endpoints)
- [🏗 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [🐛 Issue Tracking](#-issue-tracking)
- [📦 Deployment](#-deployment)
- [🔮 Future Enhancements](#-future-enhancements)
- [📜 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)
- [📬 Contact](#-contact)

---

## ✨ Features
- ✅ Add, edit, and delete **categories** (Income / Expense).  
- ✅ Track **transactions** with details like date, amount, and category.  
- ✅ Interactive **dashboard** with charts & summaries.  
- ✅ Responsive and clean **Bootstrap UI**.  
- ✅ Built using **Entity Framework Core (Code First)** with database migrations.  

---

## 🛠 Tech Stack
- **Backend:** ASP.NET Core MVC 8, C#  
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript  
- **Database:** SQL Server, Entity Framework Core  
- **Version Control:** Git & GitHub  

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Ibrahim-Suker/Expense-Tracker.git
cd Expense-Tracker
2️⃣ Configure the Database
Update the connection string in appsettings.json:

json
Copy code
"ConnectionStrings": { 
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=ExpenseTracker;Trusted_Connection=true;MultipleActiveResultSets=true" 
}
3️⃣ Apply Database Migrations
bash
Copy code
dotnet ef database update
4️⃣ Run the Application
bash
Copy code
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
bash
Copy code
Expense-Tracker/
├── Controllers/       # MVC Controllers
├── Models/            # Data models and ViewModels
├── Views/             # Razor views
├── Services/          # Business logic layer
├── Data/              # DbContext and migrations
├── wwwroot/           # Static files (CSS, JS, images)
├── appsettings.json   # Configuration
└── Program.cs         # Application entry point
🤝 Contributing
Contributions are welcome!

Fork the project

Create a feature branch

bash
Copy code
git checkout -b feature/AmazingFeature
Commit changes

bash
Copy code
git commit -m "Add some AmazingFeature"
Push to your branch

bash
Copy code
git push origin feature/AmazingFeature
Open a Pull Request

👉 Please read CONTRIBUTING.md for more details.

🐛 Issue Tracking
Found a bug 🐞? Have a feature request 💡?
Open an issue and we’ll address it promptly.

📦 Deployment
Local Deployment
bash
Copy code
dotnet publish -c Release
Docker
bash
Copy code
docker build -t expense-tracker .
docker run -p 5000:80 expense-tracker
Azure
Deploy easily using Azure App Service.

🔮 Future Enhancements
🌍 Multi-currency support

🔁 Recurring transactions

📤 Data export/import (CSV, Excel)

📱 Mobile application

🏦 Bank synchronization

📊 Advanced reporting

📈 Investment tracking

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

🙏 Acknowledgments
Bootstrap for responsive UI

Chart.js for data visualizations

Font Awesome for icons

📬 Contact
👤 Ibrahim Suker
📧 Email: ibrahimsukeroo@gmail.com
🌐 GitHub: @Ibrahim-Suker

🔗 Project Link: Expense Tracker
