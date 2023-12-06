# ToDo App

This is a simple to-do list application created in Python using the Flet library and SQLite as the database. The app allows adding, marking as complete or incomplete, and viewing tasks.

## Prerequisites

- Python 3.x
- [Flet](https://github.com/BecameTrue/flet) - A library for creating simple graphical interfaces in Python.
- SQLite - An embedded database in Python.

## Installation

1. Clone or download this repository.
2. Install dependencies by running:

   ```bash
   pip install flet
   ```

## Execution

Run the application with the following command:

```bash
python3 filename.py
```

Make sure you have Python 3 installed and accessible in your environment. If using a virtual environment, activate it before running the script.

## Features

- **Add Task:** Enter a task in the text field and click the add button to add it to the list.

- **Mark as Complete/Incomplete:** Use the checkboxes next to each task to mark them as complete or incomplete.

- **Filter by Status:** Use the "All," "In Progress," and "Completed" tabs to view tasks based on their status.

## Code Structure

- `ToDo`: Main class defining the application interface and interacting with the SQLite database.
- `db_execute`: Function to execute SQL queries on the database.
- `set_value`: Updates the `task` variable with the value from the text field.
- `add`: Adds a new task to the database.
- `checked`: Updates the status of a task (complete/incomplete) in the database.
- `tasks_container`: Creates a task container using the Flet library.
- `update_task_list`: Dynamically updates the displayed task list in the interface.
- `tabs_changed`: Updates the task list based on the selected tab.

## Author

Tais Figueiredo

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Please replace `filename.py` with the actual name of your Python file. Also, fill in the author and license information as appropriate for your project.
