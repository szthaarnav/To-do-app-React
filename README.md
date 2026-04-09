# To-do App (React)

A simple and interactive to-do list application built with React. Users can add new tasks, edit existing tasks, and delete tasks from the list. The project is designed to demonstrate core React fundamentals such as component-based structure, state management, controlled inputs, and event-driven UI updates.

---

## Features

- Add tasks using an input field and submit button
- Edit/update tasks directly in the list (inline update behavior via `setUpdate`)
- Delete tasks using a trash icon (FontAwesome)
- Controlled form input with real-time state updates
- Unique task keys generated using timestamps (`Date.now()`)

---

## Tech Stack

- **React** (Class Components)
- **JavaScript (ES6+)**
- **CSS**
- **FontAwesome** (trash/delete icon)

---

## Project Structure (High Level)

- `src/App.js` — Main component that manages app state (`items`, `currentItem`) and core handlers (`addItem`, `handleInput`, `deleteItem`, `setUpdate`)
- `src/ListItems.js` — Renders the list of tasks and provides UI for delete/update actions
- `src/App.css` / `src/ListItems.css` — Styling for the app UI

---

## Getting Started

### Prerequisites
Make sure you have the following installed:
- **Node.js** (LTS recommended)
- **npm** or **yarn**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/szthaarnav/To-do-app-React.git
```

2. Navigate into the project directory:
```bash
   cd To-do-app-React
```

3.Install dependencies:
```bash
   npm install
```
Then open
- http://localhost:3000

### Running Tests

This project includes a basic React render test (src/App.test.js).

Run tests with:
```bash
   npm test
```