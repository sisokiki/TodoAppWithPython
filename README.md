📝 To Do List
A simple desktop To-Do List application built using Python and Tkinter. This is my first Python project, created to practice GUI development and basic file handling. The app allows users to add and delete tasks, with persistent local storage.

![image](https://github.com/user-attachments/assets/ce9e589e-472e-422d-b9ff-a0caebe878f1)
![image](https://github.com/user-attachments/assets/5664e9db-a18f-4e13-8b19-420d61a556d8)

🚀 Features
Add new tasks to your list

Delete completed tasks

Tasks are saved locally in a .txt file (tasklist.txt)

User-friendly graphical interface

All assets and data are stored locally — no external database required

📂 Project Structure
bash
Copy
Edit


📁 ToDoList/
├── main.py              # Main File
├── tasklist.txt         # Auto-generated on first run
├── task.png             # Icons used in UI
├── delete.png           # Icons used in UI
├── topbar.png           # Icons used in UI
├── dock.png             # Icons used in UI
└── README.md

✅ Getting Started
Prerequisites
Python 3.10+ (Developed using Python 3.10, should work on later versions)

Installation
Clone the repository

bash
Copy
Edit
git clone -> https://github.com/sisokiki/TodoAppWithPython

cd todo-list
Run the app

bash
Copy
Edit
python main.py
That’s it! The app will launch in a window where you can start managing your tasks.

🖼️ Notes
All UI assets (icons and images) are included in the repository.

The task list is saved to tasklist.txt in the same directory as the script. Make sure the app has write permissions in the directory.

🔧 Future Improvements (Optional)
Although the app works well in its current form, here are a few ideas for future enhancements:

Edit tasks inline

Add due dates or priorities

Drag-and-drop task ordering

Save tasks to a cloud database or sync across devices

📌 Final Notes
This project was built in 2022 as my first Python GUI application, using the built-in tkinter library. It’s a great foundation for beginners learning how to create desktop apps and handle local file storage.
