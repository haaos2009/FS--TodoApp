# React Todo App

A robust, feature-rich Todo application built with **React**, **TypeScript**, and **React Context API**. Designed following clean code practices and component-based architecture, this app provides a seamless task management experience with persistent local storage and advanced inline-editing capabilities.

## Live Preview
- [Live Demo](https://haaos2009.github.io/FS--TodoApp/)

## Technologies Used
- **React** (Functional Components & Custom Hooks)
- **TypeScript** (Strict typing for components, state, and context)
- **React Context API** (Global state management without prop drilling)
- **HTML5 LocalStorage** (Data persistence across browser sessions)
- **CSS3 / BEM Methodology** (Responsive and clean styling)

## Getting started
To set up the project locally, follow these steps:

1. **Clone the repository:**

  git clone https://github.com/haaos2009/FS--TodoApp.git
  cd FS--TodoApp

2. **Install dependencies:**

  npm install

3. **Run the project locally:**

  npm start


## Key Features
- **Global State Management:** Centralized logic utilizing `React Context` and custom hooks (`useTodos`).
- **Data Persistence:** Automatically syncs and saves tasks to `localStorage` using `JSON.stringify/parse`.
- **Task Filtering:** Instantly filter tasks by status (`All`, `Active`, `Completed`).
- **Bulk Actions:** Toggle all tasks simultaneously or clear all completed tasks in one click (with dynamic button states).
- **Inline Editing:**
  - Double-click any task title to activate the edit mode.
  - Press `Enter` or trigger `onBlur` to save changes.
  - Press `Escape` to cancel editing instantly.
  - Automatic text trimming; empty titles automatically remove the todo item.
- **Smart Focus Management:** Auto-focuses the input field on initial load and after clearing/deleting tasks.
- **Active Counter:** Real-time indicator displaying the number of remaining active tasks.
