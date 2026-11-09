# To-Do List Application

A simple and interactive To-Do List application built using HTML, CSS, and JavaScript. It helps users organize daily tasks, track their progress, and manage completed and pending activities.

## Features

- **Add Tasks:** Create new tasks using the Add button.
- **Quick Entry:** Press Enter to add a task.
- **Mark as Completed:** Check tasks to mark them as completed.
- **Delete Tasks:** Remove tasks that are no longer needed.
- **Local Storage:** Save tasks in the browser's Local Storage.
- **Data Persistence:** Previously saved tasks are restored when the application is reopened.

## Tech Stack

- **HTML5** – Application structure.
- **CSS3** – Styling and layout.
- **JavaScript (Vanilla JS)** – Application logic and DOM manipulation.
- **Bootstrap 4** – Responsive layout and utility classes.
- **Font Awesome** – Icons.
- **Browser Local Storage** – Task data persistence.

## Project Structure

```text
To_Do_List/
│
├── To_Do_List.html
├── To_Do_List.css
└── To_Do_List.js
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Vishal4536/To_Do_List.git
```

### 2. Navigate to the Project Directory

```bash
cd To_Do_List
```

### 3. Run the Application

Open `To_Do_List.html` in your browser.

Alternatively, use the Live Server extension in VS Code for a local development environment.

## How to Use

1. Enter your task in the input field.
2. Click **Add** or press Enter to create a task.
3. Use the checkbox to mark a task as completed.
4. Click the trash icon to delete a task.
5. Click **Save** to store your updated task list in Local Storage.

## Data Persistence

The application uses the browser's `localStorage` API to store task information.

Tasks are saved as JSON data and restored when the application loads again. Changes are persisted when the Save button is clicked.

## Future Improvements

- Add an option to edit existing tasks.
- Implement task filtering (All, Pending, Completed).
- Add task priority levels.
- Improve the UI with responsive design enhancements.

---

**Built with HTML, CSS, and JavaScript.**
