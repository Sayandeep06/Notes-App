# Notes App 

A simple React-based Todo App that helps you manage and organize tasks efficiently. You can add, edit, delete, and mark tasks as completed.

![Screenshot of the Todo App](./Screenshot%202024-12-01%20at%205.06.31%20AM.png)
## Features

- ****Add a Task****: Quickly add a new task with a simple input form.

- ****Edit a Task****: Edit the task description after it's added.

- ****Delete a Task****: Remove tasks you no longer need.

- ****Mark as Completed****: Toggle the completion status of tasks.

## Technologies Used

- ****React****: JavaScript library for building user interfaces.

- ****UUID****: Used for generating unique identifiers for each task.

- ****FontAwesome****: Used for the edit and delete icons.

## Setup

To run this project locally, follow these steps:

1. Clone the repository:

 ```

 git clone https://github.com/your-username/todo-app.git
 
 ```

2.  Navigate to the project directory:

```
cd todo-app
```

3.  Install the dependencies:

```
npm install
```

4.  Run the application:
```
npm start
```
Your app should now be running at http://localhost:5173.

**File Structure**
```
src/

├── components/

│  ├── EditTodoForm.js

│  ├── Todo.js

│  └── TodoForm.js

├── TodoWrapper.js

└── index.js
```

**How It Works**

1.  **TodoWrapper.js**: This is the main container that holds the list of tasks (todos). It manages the state of the todos and provides functions to add, edit, delete, and toggle tasks.

2.  **TodoForm.js**: A form where users can input new tasks to be added to the todo list.

3.  **EditTodoForm.js**: A form for editing existing tasks.

4.  **Todo.js**: Displays individual tasks, allowing you to mark them as completed or delete them.

5.  **uuid**: Each task is assigned a unique ID using the uuid library to ensure that each task can be properly identified.
