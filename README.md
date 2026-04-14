# Minimalist Project Manager

A lightweight, Timestripe-inspired Kanban board built entirely in a single file using pure HTML, CSS, and Vanilla JavaScript. It requires no database, no backend, and no external libraries. Everything is saved instantly to your browser's Local Storage.

## 🌟 Features

* **Zero Setup:** Just double-click the `index.html` file and start working.
* **Local Storage:** All your columns, tasks, and notes are saved directly in your browser.
* **Drag & Drop:** Seamlessly drag cards to reorder them or move them across different project columns.
* **Smart Subtasks:** Type `[]` inside any task's description to instantly generate interactive checkboxes.
* **Priority Colors:** Right-click any card to assign priority colors (P1 Red, P2 Orange, P3 Green).
* **Auto-Sorting:** Completing a task automatically fades it out and moves it to the bottom of your list.
* **Dynamic UX:** The browser tab updates to match your current task, and keyboard shortcuts (Enter/Tab/Escape) make navigation a breeze.

## 📖 How to Use

* **Add a Project Column:** Click the floating `+` button in the bottom right corner of the screen.
* **Rename a Column:** Double-click on any column's title to edit it. Press `Enter` to save.
* **Add a Task:** Click the small `+` icon next to a project's name.
* **Edit a Task:** Click on any task card. The title will auto-focus so you can start typing immediately. Press `Tab` or `Enter` to jump into the description area.
* **Set Priorities:** Right-click on a task card (without opening it) to open the context menu. Select a color to set the priority or delete the task.
* **Complete a Task:** Click the checkbox directly on the task card from the board view. It will fade out and drop to the bottom of the list.

## 🛠️ Customizing the Tool (Powered by AI)

Because this entire application lives inside a single `index.html` file, it is incredibly easy to modify, upgrade, and personalize without knowing how to code.

**Want to add Dark Mode? Need to add a due-date feature? Want different colors?**
1. Open the `index.html` file in a text editor (like Notepad, TextEdit, or VS Code).
2. Copy all the code.
3. Go to any AI model (like ChatGPT, Gemini, or Claude).
4. Paste the code and prompt the AI with what you want. *(Example: "Here is my project manager code. Please update the CSS to make it a dark-mode theme.")*
5. Copy the updated code the AI gives you, paste it back into your `index.html` file, and save!

Feel free to **fork** this project, tweak it to your exact workflow needs, and make it your own!

## 🚀 How to Run

There are no dependencies, no `npm install`, and no servers to start.
1. Download or clone this repository.
2. Double-click `index.html`.
3. It will open in your default web browser and is ready to use immediately.
