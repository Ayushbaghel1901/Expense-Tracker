# 💰 Expense Tracker (Python HTTP Server + SQLite)

## 📌 Project Description

Expense Tracker is a lightweight backend-based web application built using Python’s built-in HTTP server and SQLite database.
It allows users to manage daily expenses, track monthly salary, calculate savings, and export expense data as CSV.

This project is built without using any external frameworks like Flask or Django, making it simple and beginner-friendly.

This project is being developed collaboratively by **Ayush Baghel** and **Diya Panjwani**.

---

## 🚀 Features

### 🧾 Expense Management

* Add new expenses
* Update existing expenses
* Delete expenses
* View all expenses sorted by date

### 💵 Salary Tracking

* Set monthly salary
* Calculate total expenses
* View remaining balance
* Calculate monthly savings automatically

### 📊 Analytics & Reports

* Category-wise expense summary
* Monthly expense summary
* Top 5 categories overview
* Monthly savings report

### 📁 Export Functionality

* Export all expenses as CSV file

---

## 🛠 Technologies Used

* Python 3
* http.server (Built-in Python module)
* SQLite (sqlite3)
* JSON
* CSV
* REST API architecture

No external libraries required.

---

## 📂 Project Structure

```
expense-tracker/
│
├── server.py
├── database.py
├── models.py
├── routes.py
├── utils.py
│
├── expense.db
│
├── static/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### Clone the repository

```
git clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker
```

### Run the server

```
python server.py
```

### Open in browser

```
http://localhost:8000
```

---

## 📡 API Endpoints

### Add Expense

```
POST /expenses
```

Example JSON

```
{
  "title": "Groceries",
  "amount": 500,
  "category": "Food",
  "date": "2026-03-15"
}
```

### Get All Expenses

```
GET /expenses
```

### Update Expense

```
PUT /expenses/{id}
```

### Delete Expense

```
DELETE /expenses/{id}
```

### Export CSV

```
GET /export
```

---

## 📊 Example Output

```
Total Salary: ₹50,000
Total Expenses: ₹18,000
Remaining Balance: ₹32,000
Savings: ₹32,000
```

---

## 👥 Contributors

This project is developed collaboratively by:

* **Ayush Baghel**
* **Diya Panjwani**

---

## 🎯 Future Improvements

* User authentication
* Category-based charts and analytics
* Mobile-friendly UI
* React frontend integration
* Cloud database support

---

## 📜 License

This project is open-source and available under the **MIT License**.
