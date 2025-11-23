# CSV → Kanban (Offline)

A single-file, offline Kanban board application that converts CSV data to an interactive task management board.

## Features

- **Offline-first**: Works entirely in your browser with no network required
- **CSV Import/Export**: Upload CSV files to create boards, export your data back to CSV or JSON
- **Drag & Drop**: Smoothly move tasks between columns and reorder them
- **Task Management**: Add, edit, and delete tasks with rich metadata
- **Tag System**: Organize tasks with tags and multi-highlight functionality
- **Priority & Due Dates**: Set priority levels and due dates for tasks
- **Local Storage**: All data persists locally in your browser
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Mode**: Automatic dark mode support based on system preferences

## Getting Started

1. Open `index.html` in your web browser - no installation required
2. Click "Template CSV" to download an example file
3. Upload your own CSV file or use the template to get started
4. Start managing your tasks!

## CSV Format

The application expects CSV files with these columns:
- `id` (optional): Unique task identifier
- `title` (required): Task title
- `description` (optional): Task description
- `status` (required): Column name (defaults: To Do, In Progress, Done)
- `priority` (optional): Priority level (Low, Medium, High)
- `due_date` (optional): Due date in YYYY-MM-DD format
- `tags` (optional): Tags separated by semicolons or commas

## Usage

- **Upload CSV**: Click "Upload CSV" to import your data
- **Add Tasks**: Click "+ Add Task" in any column
- **Edit Tasks**: Click the edit button on any task card
- **Delete Tasks**: Click the delete button on any task card
- **Move Tasks**: Drag and drop tasks between columns
- **Highlight Tags**: Click tag chips to highlight all tasks with that tag
- **Export Data**: Export your board as CSV or JSON for backup

## Keyboard Shortcuts

- `Ctrl/Cmd + N`: Create new task
- `Escape`: Close modal dialogs
- `Tab`: Navigate between elements
- `Space/Enter`: Toggle tag highlights

## Data Persistence

All data is stored locally in your browser's localStorage. Click "Reset" to clear all data and start fresh.