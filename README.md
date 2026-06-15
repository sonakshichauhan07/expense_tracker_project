# 💰 Expense Tracker

A simple and efficient command-line Expense Tracker application built with Python. This project helps users record daily expenses, view expense history, and track total spending.

---

## 📌 Project Description

Managing personal finances is an important skill. This Expense Tracker allows users to maintain a record of their expenses directly from the command line. The application provides a user-friendly menu to add new expenses, view existing expenses, and calculate the total amount spent.

This project is ideal for Python beginners who want to learn:

- Lists and dictionaries
- Loops and conditional statements
- Functions
- User input handling
- Basic data management

---

## 🚀 Features

### Add Expense

Users can enter:

- Expense name
- Expense amount

The expense is stored in memory for the current session.

### View Expenses

Displays all recorded expenses along with their amounts.

### Calculate Total Expense

Automatically calculates and displays the total amount spent.

### Menu-Driven Interface

Easy-to-use command-line menu for smooth navigation.

---

## 📂 Project Structure

```text
expense_tracker_project/
│
├── expense_tracker.py
├── README.md
│
└── future/
    ├── data.csv
    └── database.db
```

---

## 🛠️ Requirements

- Python 3.8 or above

Check your Python version:

```bash
python --version
```

---

## ▶️ How to Run

### Step 1: Download or Clone the Project

```bash
git clone <repository-url>
```

Or download the ZIP file and extract it.

### Step 2: Navigate to the Project Folder

```bash
cd expense_tracker_project
```

### Step 3: Run the Application

```bash
python expense_tracker.py
```

---

## 📸 Sample Execution

```text
===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 1

Enter expense name: Aman Rathore
Enter amount: 50000

Expense added successfully!

===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 2

Expenses:
Aman Rathore - ₹50000.0

===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 3

Total Expense: ₹50000.0

===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 1

Enter expense name: Sonkashi Chauhan
Enter amount: 600000

Expense added successfully!

===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 2

Expenses:
Aman Rathore - ₹50000.0
Sonkashi Chauhan - ₹600000.0

===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 3

Total Expense: ₹650000.0

===== Expense Tracker =====
1. Add Expense
2. View Expenses
3. Show Total Expense
4. Exit
Enter your choice: 4

Thank you for using Expense Tracker!
```

---

## 🧠 Concepts Used

This project demonstrates:

- Variables
- Lists
- Dictionaries
- Loops (`while`)
- Conditional Statements (`if-elif-else`)
- User Input (`input()`)
- Basic Data Processing

---

## 🔄 Future Improvements

The following features can be added in future versions:

### Data Persistence

- Save expenses to CSV files
- Save expenses to JSON files
- Store expenses in SQLite database

### Expense Categories

- Food
- Travel
- Shopping
- Bills
- Entertainment

### Reports & Analytics

- Daily reports
- Weekly reports
- Monthly reports
- Yearly reports

### Data Visualization

Create visual reports using:

```python
matplotlib
pandas
```

Examples:

- Pie Charts
- Bar Charts
- Monthly Expense Trends
- Category-wise Spending Analysis

### GUI Version

Build a desktop application using:

```python
Tkinter
```

or

```python
PyQt
```

### Web Version

Develop a web-based expense tracker using:

- Flask
- Django
- HTML
- CSS
- JavaScript

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

- How to create interactive command-line applications
- How to manage data using Python collections
- How to structure a Python project
- How to handle user inputs efficiently
- How to extend a basic project into a real-world application

---

## 📈 Possible Enhancements

- User Authentication
- Multi-user Support
- Expense Search Feature
- Expense Editing and Deletion
- Export Reports to Excel
- Dashboard with Graphs
- Cloud Database Integration

---

## 👨‍💻 Author

**Sonakshi chauhan**

BCA student | Python Learner | Aspiring Software Developer

This project was created to practice Python fundamentals and gain hands-on experience in building real-world applications.

---

## 📜 License

This project is open-source and can be used for educational and personal learning purposes.

---

## ⭐ Acknowledgements

Special thanks to the Python community and open-source contributors for providing excellent learning resources and documentation.
