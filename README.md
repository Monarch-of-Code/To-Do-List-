# To-Do List

A simple and polished task management app built with HTML, CSS, and JavaScript. It lets users add, complete, remove, and persist to-do items in the browser using local storage.

## Features

- Add new tasks from the input field
- Mark tasks as completed by clicking on them
- Remove tasks using the trash icon
- Persist tasks across page refreshes with browser local storage
- Clean, responsive, glassmorphism-inspired UI

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome for icons

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd To-Do-List-
   ```
3. Open [index.html](index.html) in your browser.

No build step or package installation is required.

## Environment Variables

No environment variables are required for this project.

## API Routes / Endpoints

This project does not use a backend or expose API routes.

## Usage

1. Open the app in your browser.
2. Enter a task in the input box.
3. Click the Add button to create the task.
4. Click a task to toggle its completed state.
5. Click the trash icon to delete a task.

Tasks are automatically saved in the browser and restored when you reopen the page.

## Folder Structure

```text
To-Do-List-/
├── index.html        # Main structure of the UI
├── style.css         # Styling and layout for the app
├── main.js           # Task logic, event handling, and local storage
└── README.md         # Project documentation
```

## Notes / Warnings

- The app relies on browser local storage, so data is stored only on the device/browser where it is created.
- Clearing browser storage or using a different browser/profile will remove saved tasks.
- The interface currently uses a CDN-based Font Awesome stylesheet, so an internet connection is required for the icons to load.

## Author

**Muhammad Muzammil** (Monarch of Code) — Full Stack Developer
