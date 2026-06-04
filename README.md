# TaskFlow — Simple Task Manager

TaskFlow is a simple task manager built with HTML, CSS, and JavaScript. It allows users to add tasks, mark tasks as completed, delete tasks, and filter tasks by all, active, or completed.

## Features

- Add a new task
- Add tasks by pressing the Enter key
- Mark tasks as completed using a checkbox
- Delete tasks from the list
- Filter tasks by:
  - All
  - Active
  - Completed
- View the number of active tasks remaining
- Empty state message when there are no tasks

## Technologies Used

- HTML
- CSS
- JavaScript

## How It Works

The app stores tasks in a JavaScript array. Each task has an `id`, `text`, and `completed` status.

When a task is added, it is saved into the array and displayed on the page. The user can then complete, delete, or filter tasks.

## Project Structure

```text
project-folder/
│
├── index.html
├── app.js
└── README.md