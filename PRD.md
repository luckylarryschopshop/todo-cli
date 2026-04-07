# PRD.md

## Product Overview

This is a single-page task manager web application designed to help users manage their daily tasks. The app features a dark theme for improved readability and user comfort. Tasks are stored in the browser's localStorage, allowing users to persist their data across sessions without the need for a backend server.

## User Stories

1. As a user, I want to add a new task so that I can keep track of my to-do items.
2. As a user, I want to mark a task as complete so that I can track my progress.
3. As a user, I want to delete a task so that I can remove items that are no longer needed.
4. As a user, I want to filter tasks by their status (all, active, completed) so that I can focus on specific tasks.
5. As a user, I want to clear all completed tasks so that I can keep my task list clean.

## Acceptance Criteria

- Users can add a task by typing in a text input and pressing "Enter" or clicking "Add".
- Tasks are displayed in a list below the input field.
- Each task includes a checkbox to mark it as complete, a label for the task text, and a delete button.
- Users can click on filter buttons (All, Active, Completed) to show only tasks of a specific status.
- A "Clear Completed" button is available to remove all completed tasks.
- Tasks are saved in localStorage so that they persist after the page is refreshed or closed.
- The app uses a dark theme for the background and text colors.

## UI Wireframe

- **Input Field**: At the top of the page, a text input with a placeholder "Add a new task" and an "Add" button.
- **Task List**: Below the input, a list of tasks with checkboxes, task text, and delete buttons.
- **Filter Buttons**: At the bottom of the page, three buttons labeled "All", "Active", and "Completed" to filter the task list.
- **Clear Completed Button**: A button labeled "Clear Completed" located next to the filter buttons.

## Tech Stack

- **Frontend**: HTML, CSS, and JavaScript
- **Data Storage**: localStorage
- **No Backend**: The app does not require a server or API for functionality.