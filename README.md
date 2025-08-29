# 💰 Expense Tracker

A simple and intuitive **Expense Tracker** web application to manage your income, expenses, and balance.  
Built with **ASP.NET Core MVC** and **Entity Framework Core (Code-First Approach)**.

---

## 🚀 Features
- 📊 **Dashboard Overview** – Total income, expense, and balance visualization.  
- 🗂 **Category-wise Breakdown** – Expenses grouped by categories.  
- 📈 **Charts & Graphs** – Income vs Expense graph with daily tracking.  
- 📝 **Transaction Management** – Add, edit, and delete transactions.  
- 🔍 **Recent Transactions** – Quick view of your latest financial activities.  
- 🎨 **Modern Dark UI** – Clean, responsive design with data visualization.

---

## 🖼 Screenshots

### Dashboard  
![Dashboard Screenshot](/mnt/data/FireShot%20Capture%20006%20-%20Expense%20Tracker%20-%20%5Blocalhost%5D.png)

### Transactions Page  
![Transactions Screenshot](/mnt/data/FireShot%20Capture%20007%20-%20Expense%20Tracker%20-%20%5Blocalhost%5D.png)

### Add Transaction  
![Add Transaction Screenshot](screenshots/add-transaction.png)

### Expense by Category  
![Expense by Category Screenshot](screenshots/expense-category.png)

### Income vs Expense Graph  
![Income vs Expense Screenshot](screenshots/income-expense.png)

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, Bootstrap, Syncfusion UI  
- **Backend:** ASP.NET Core MVC (.NET 8)  
- **Database:** SQL Server (EF Core – Code First)  
- **Tools:** Git, Visual Studio, LINQ  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ibrahim-Suker/Expense-Tracker.git
Navigate to the project folder:

bash
Copy code
cd Expense-Tracker
Update the connection string in appsettings.json:

json
Copy code
"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=ExpenseTracker;Trusted_Connection=true;MultipleActiveResultSets=true"
}
Apply migrations:

bash
Copy code
dotnet ef database update
Run the application:

bash
Copy code
dotnet run
Open in browser:
👉 https://localhost:5001

📌 Usage
➕ Add Transaction: Navigate to Transactions → Add New Transaction.

✏️ Edit Transaction: Update existing transactions.

❌ Delete Transaction: Remove unwanted transactions.

📊 View Dashboard: See summary charts and recent activities.

📷 Screenshots Folder
Make sure to place your extra screenshots in a folder named screenshots/ inside the project root.

<img width="1521" height="1066" alt="FireShot Capture 007 - Expense Tracker -  localhost" src="https://github.com/user-attachments/assets/99770ed8-2bb9-49e4-a2a1-89a3ca7fe238" />
<img width="1521" height="1560" alt="FireShot Capture 006 - Expense Tracker -  localhost" src="https://github.com/user-attachments/assets/011b4e51-2b27-42ba-91c3-398845252919" />

<img width="1521" height="883" alt="FireShot Capture 008 - Expense Tracker -  localhost" src="https://github.com/user-attachments/assets/02158ebc-3572-45a2-a383-376790c64f2b" />

<img width="1920" height="1037" alt="FireShot Capture 009 - Expense Tracker -  localhost" src="https://github.com/user-attachments/assets/71351aa4-f83e-41c4-9738-bb89ea89da3c" />
<img width="1920" height="1037" alt="FireShot Capture 010 - Expense Tracker -  localhost" src="https://github.com/user-attachments/assets/5d46314f-9653-4cf8-9c98-7f8bdb5dde43" />



🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open a Pull Request or Issue.

📜 License
This project is licensed under the MIT License.
