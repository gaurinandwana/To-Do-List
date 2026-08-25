# 📝 To-Do List

A simple Python-based **To-Do List application** that helps users manage daily tasks. The application allows users to add, view, complete, and delete tasks while automatically saving their data locally.

## ✨ Features

* ➕ Add new tasks
* 📋 View all tasks
* ✅ Mark tasks as completed
* 🗑️ Delete tasks
* 📊 View task statistics
* 📈 Calculate task completion rate
* 💾 Automatically save tasks using a CSV file
* 🖥️ Simple interactive command-line interface

## 🛠️ Technologies Used

* **Python**
* **Pandas** — for managing task data
* **CSV** — for local data storage
* **Google Colab** — development environment

## 🚀 How to Run

### 1. Open Google Colab

Create a new notebook in Google Colab.

### 2. Install Pandas

```bash
pip install pandas
```

### 3. Run the Python code

Run the cells in order. The application will automatically create a `todo_list.csv` file for storing your tasks.

## 📖 How to Use

After running the program, the following menu will appear:

```text
========================================
📝 TO-DO LIST
========================================

1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. View Statistics
6. Exit
```

Enter the corresponding number to perform an action.

### Example

Adding a task:

```text
Enter your choice: 1
Enter task: Complete DSA assignment
✅ Task added: Complete DSA assignment
```

Viewing tasks:

```text
📋 YOUR TO-DO LIST
----------------------------------------
1. ⬜ Complete DSA assignment - Pending
2. ⬜ Read Python documentation - Pending
3. ✅ Submit internship application - Completed
```

Viewing statistics:

```text
📊 TASK STATISTICS
------------------------------
Total tasks     : 3
Completed tasks : 1
Pending tasks   : 2
Completion rate : 33.3%
```

## 📂 Project Structure

```text
To-Do-List/
│
├── todo_list.py
├── todo_list.csv
└── README.md
```

## 🔮 Future Improvements

* [ ] Add task priorities
* [ ] Add deadlines and due dates
* [ ] Add task categories
* [ ] Add task search and filtering
* [ ] Add reminders
* [ ] Add a graphical user interface
* [ ] Add SQLite database support
* [ ] Add weekly productivity reports
* [ ] Add user authentication

## 🎯 Learning Outcomes

This project demonstrates practical use of:

* Python functions
* Loops and conditional statements
* File handling
* Pandas DataFrames
* CSV data persistence
* User input and validation
* Basic data analysis
* Building a command-line application

## 👩‍💻 Author

**Gauri Nandwana**

B.Tech Computer Science Engineering
VIT Bhopal University
