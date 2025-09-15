# Smart Contact Form 📧

A responsive and interactive contact form featuring real-time, debounced validation and a message history panel that persists data using the browser's `localStorage`.



---

## Features

* **Real-time Validation**: Instant feedback on Name, Email, and Message fields as the user types.
* **Debounced Input**: Validation logic runs 300ms after the user stops typing, ensuring a smooth user experience and better performance.
* **Persistent Message History**: Submitted messages are saved in `localStorage` and displayed in a history panel below the form, surviving page reloads.
* **Delete Functionality**: Users can remove individual messages from the history with a single click.
* **Event Delegation**: Efficiently handles all delete actions with a single event listener attached to the history container.
* **Success Feedback**: Displays a confirmation message upon successful submission without reloading the page.
* **Graceful Error Handling**: Includes `try...catch` blocks to manage potential `localStorage` errors without crashing the application.

---

## Tech Stack

* **HTML5**: For the structure and content of the form.
* **CSS3**: For styling, layout (using Flexbox), and responsiveness.
* **JavaScript (ES6+)**: For all dynamic functionality, including DOM manipulation, validation, event handling, and `localStorage` management.

---

## How to Run

1.  **Download or Clone**: Get the project files onto your local machine.
2.  **Navigate to Directory**: Open the `contact-form/` folder.
3.  **Open in Browser**: Double-click the `index.html` file to open it in your preferred web browser (e.g., Chrome, Firefox, Edge).

---

## File Structure

The project is organized into three separate files for clarity and maintainability.


# Dynamic Todo List with Search ✅

A feature-rich todo list application that allows users to add, manage, and filter tasks. It includes a debounced search functionality and persists all data using `localStorage`, ensuring no data is lost between sessions.



---

## Features

* **Full CRUD Functionality**: Users can **C**reate, **R**ead, **U**pdate (mark as complete), and **D**elete todos.
* **Debounced Search**: A live search bar filters todos by text as you type, with a 400ms delay to prevent excessive re-rendering and improve performance.
* **Category Filters**: Instantly filter the todo list by three states: **All**, **Active**, and **Completed**.
* **Persistent Storage**: All todos are saved to the browser's `localStorage`, so your list is preserved even after closing the tab or browser.
* **Live Todo Counter**: A counter at the top of the list provides a real-time summary of total and completed tasks.
* **Efficient Event Handling**: Uses **event delegation** to manage all todo interactions (completion and deletion) with a single event listener on the list container.
* **Clean UI**: A modern and responsive user interface that provides clear feedback for all actions.

---

## Tech Stack

* **HTML5**: Provides the semantic structure for the application.
* **CSS3**: Used for modern styling, layout with Flexbox, and a responsive design.
* **JavaScript (ES6+)**: Powers all the dynamic features, state management, and interaction with `localStorage`.

---

## How to Run

1.  **Download or Clone**: Get the project files onto your local machine.
2.  **Navigate to Directory**: Open the `todo-app/` folder.
3.  **Open in Browser**: Double-click the `index.html` file to launch the application in your web browser.

---

## File Structure

The project maintains a clear separation of concerns with its structure.
