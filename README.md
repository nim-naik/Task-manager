# 📝 Task Manager

A simple command-line Task Manager written in Python.  
This tool allows users to sign up, log in, manage their personal information, and track tasks with status updates. 🚀

## ✨ Features

- 🔐 **User Signup & Login**: Securely create an account and log in using a username and password.
- 🏠 **Personal Information Storage**: Stores name, address, and age.
- ✅ **Task Management**:
  - ➕ Add multiple tasks with targets.
  - 🔄 Update the status of tasks (completed, ongoing, not started).
  - 👀 View all tasks and statuses.
- 💾 **Data Persistence**: All user data and tasks are stored in plain text files.

## 🚀 Getting Started

### 🛠️ Prerequisites

- Python 3.x installed on your system.
- PyCharm IDE.

### ▶️ Running the Program

1. **Clone or Download** this repository.
2. Open a terminal and navigate to the project directory.
3. Run the script:
 bash command
 python your_script_name.py
4. Follow the on-screen prompts:
- Type `1` if you are a new user to sign up.
- Type `0` if you already have an account to log in.

## 📁 File Structure

- Each user has a file named `<username> task.txt` for personal info and tasks.
- Task status updates are saved in `<username>Task.txt`.
- There is a text file present in 

## 🔍 How It Works

### 🆕 Signup

- Enter a username and password.
- Provide your name, address, and age.
- Your information is saved in a file.

### 🔑 Login

- Enter your username and password.
- If credentials match, you can:
- 📄 View your data
- ➕ Add new tasks
- 📝 Update task statuses
- 👁️ View task status history

### 📋 Task Management

- **Add Tasks**: Specify the number of tasks, their descriptions, and targets.
- **Update Tasks**: Mark tasks as completed, ongoing, or not started.
- **View Tasks**: See all your tasks and their statuses.

## ⚠️ Notes & Limitations

- 🔒 **Security**: Passwords are stored in plain text. Do **not** use real or sensitive credentials.
- 📂 **File Handling**: All data is stored in local text files. There is no database or encryption.
- 🧑‍💻 **User Experience**: The script is designed for educational/demo purposes and uses basic input/output.

Enjoy managing your tasks! 🎉
