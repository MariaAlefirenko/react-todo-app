# ✅ Todo App

A **modern React Todo application** with full CRUD functionality for a single user.
This project demonstrates advanced React patterns, state management, API interactions, loaders, notifications, and filtering.

> **Note:** The app works for a single user only and is intended for testing and demonstration purposes.

---

## 🔗 Live Preview

👉 **[View Live on GitHub Pages](https://mariaalefirenko.github.io/react-todo-app/)**

---

## 🧰 Technologies Used

- **React** – component-based architecture
- **JavaScript / TypeScript** – core logic and type safety
- **SCSS** – styling and responsive layout
- **HTML5** – semantic markup
- **Fetch** – API requests
- **Prettier** – code formatting (configured via VSCode)

---

## 🌟 Key Features

### 📝 Todos Management

- **Adding:** Add new todos with **temporary state** (`tempTodo`) and a **loader indicator**.
- **Editing:** Edit todo titles on **double-click**. Submit on form submit, `blur`, **`Esc`** key, and delete if the title is empty.
- **Deleting:** Delete **individual** todos or **all completed** todos at once.
- **Status Toggle:** Toggle the **completed status** for single todos.
- **Batch Toggle:** Toggle the status of **all todos** with a single checkbox.

### 🔎 Filtering & Searching

- **Filtering:** Filter todos by status: **All**, **Active**, and **Completed**.
- **Searching:** Search todos by title using a clearable input field.

### 🎨 User Interface

- **Loader:** **Overlay loader** displayed during API requests.
- **Modal:** Modal window for displaying selected todo **details**.
- **Notifications:** Notifications for **API errors** (on add/update/delete).
- **Design:** **Responsive** and **minimalistic** design.

### 💻 Code & UX Enhancements

- **Formatting:** **Prettier** formatting on save.
- **Reusable Components:** Built using **reusable components** (App, TodosList, TodoFilter, TodoModal, Loader).
- **Optimistic UI:** Implementation of **optimistic UI updates** and **temporary state** handling.

---

## 🚀 Getting Started

```bash
# Clone the repository:
git clone https://github.com/MariaAlefirenko/react-todo-app.git

# Open project folder:
cd react-todo-app

# Install dependencies:
npm install
# or
yarn install

# Run the project locally:
npm start
# or
yarn start
```
