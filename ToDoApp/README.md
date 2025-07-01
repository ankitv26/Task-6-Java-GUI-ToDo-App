# ToDoApp - Elevate Labs Internship Task 6

## Overview

This project is a simple GUI-based To-Do List application built using Java Swing. It was developed as part of Elevate Labs Internship Task 6. The application allows users to add tasks, view them in a list, and delete selected tasks through an easy-to-use graphical interface.

---

## Features

- **Add Task:** Enter a task in the input field and add it to the list.
- **View Tasks:** Displays all tasks added by the user.
- **Delete Task:** Remove the selected task from the list.
- **Input Validation:** Alerts user when trying to add an empty task or delete without selecting a task.
- **Keyboard Support:** Pressing Enter in the input field adds the task.

---

## Technologies Used

- Java SE
- Swing GUI Toolkit

---

## How to Run

    1. Ensure you have Java JDK installed (version 8 or higher recommended).
    2. Save the source code in a file named `ToDoApp.java`.
    3. Open your terminal or command prompt and navigate to the directory containing `ToDoApp.java`.
    4. Compile the program with the command:
        javac ToDoApp.java
    5. Run the program using:
        java ToDoApp
    6. The application window will open. You can now add, view, and delete tasks.

---

## Code Structure

- `ToDoApp` class extends `JFrame` and contains all GUI components.
- Uses `DefaultListModel<String>` and `JList<String>` to manage and display tasks.
- Two main buttons: **Add Task** and **Delete Selected Task**.
- The `main` method launches the GUI on the Event Dispatch Thread using `SwingUtilities.invokeLater`.

---

## Future Enhancements

- Add task persistence by saving/loading tasks from a file.
- Enable editing of existing tasks.
- Add task priorities or deadlines.
- Improve UI with advanced layouts and styling.

---

## Author

Ankit Vishwakarma <br>
Github - @ankitv26 <br>
Elevate Labs Internship Participant

---

