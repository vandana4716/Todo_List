ToDo List Application
A simple and intuitive ToDo List application built using React and Vite. This app allows users to add, delete, and manage their tasks efficiently. It also ensures that the list is preserved even after a page refresh, using local storage.

Features
Add Tasks: Users can easily add new tasks to the list.
Delete Tasks: Users can remove tasks from the list by clicking the delete button.
Persistent Data: The application uses local storage to save tasks, ensuring they are not lost on page refresh.


Usage
#Adding a Task:
Enter a task description in the input field.
Click the "Add" button to add the task to the list.

#Deleting a Task:
Click the delete icon next to a task to remove it from the list.

#Persistent Data:
The tasks are automatically saved in the browser's local storage, ensuring that the list is preserved even if you close or refresh the browser.

Components
App Component
The root component that holds the entire ToDo list application.
TodoList Component
Displays the list of tasks.
Handles the rendering of each task and provides the delete functionality.
TodoItem Component
Represents each task in the list.
Includes a delete image for removing the task.
Local Storage Integration
