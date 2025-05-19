# daily-task-planner-using-python-with-ui
Daily Task Planner 🗓️ | Python &amp; PyQt A simple task manager to add, delete, and save tasks using an interactive calendar. Features include task categorization with #hashtags and emoji support for a personalized experience. 📝💻  #Python #PyQt #TaskPlanner #Productivity #CalendarApp




🗓️ Daily Task Planner
A lightweight desktop task manager built with Python 3.13 and PyQt5, designed to help users efficiently add, save, and delete tasks for specific dates using a user-friendly calendar interface.


🧠 Project Overview
Daily Task Planner enables users to:
📅 View a monthly calendar
🔍 Select any specific date
✍️ Add tasks to the selected date
❌ Delete tasks
💾 Save tasks persistently (locally)
The intuitive interface makes daily task management simple, clean, and effective.


🔧 Development Setup
1. Install Python
 - Download Python 3.13
 - Ensure it's added to your system PATH

2. Install PyCharm IDE (optional)
Create a new project: DailyTaskPlanner

3. Install Qt Designer
pip install pyqt5-tools
pyqt5designer  # Launch Qt Designer


🖌️ UI Design with Qt Designer
Widgets used in the main window:
 - QCalendarWidget – for date selection
 - QLineEdit – to enter new tasks
 - QListWidget – to display tasks
 - QPushButton – for Add, Save, and Delete actions
File saved as: task.ui


💻 Core Functionalities
  Feature                 Description
➕ Add Task  - Enter text and click "Add New"
💾 Save Task  - Saves tasks for the selected date
❌ Delete Task  - Select a task and click "Delete Changes"
📆 Calendar UI - Navigate months and select specific dates


🧑‍💻 Tech Stack
Python 3.13
 - PyQt5 – GUI framework
 - Qt Designer – UI layout tool
 - JSON / SQLite – Task storage (choose your preferred method)


🚀 Getting Started:
# Clone the repository
git clone https://github.com/yourusername/daily-task-planner.git
cd daily-task-planner

# Install dependencies
pip install PyQt5 pyqt5-tools

# Run the app
python main.py


📂 Project Structure
daily-task-planner/
├── main.py              # Main application file
├── task.ui              # UI layout file (Qt Designer)
├── task_manager.py      # Task logic (add/save/delete)
├── README.md            # Project documentation


📌 Planned Features:
✏️ Edit existing tasks
✅ Mark tasks as completed
🔔 Task reminders/notifications
🌙 Dark mode support


📝 License
This project is open-source and available under the MIT License.

🙋‍♀️ Author
Created by Sujal Yadav.
