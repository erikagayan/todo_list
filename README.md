# ToDo List

ToDo List is a web application for managing a task list. It allows users to create, edit, delete, and track the status of tasks. Built with Django, the application also supports adding categories (tags) to tasks.

## Features

- **Create Tasks**: Users can add new tasks with content, creation date, and tags.
- **Edit Tasks**: Users can update task content, date, and completion status.
- **Delete Tasks**: Remove tasks from the list.
- **Tags**: Add tags to tasks and view a list of all tags.
- **Track Completion**: Mark tasks as completed or not completed.


## Testing

This project includes unit tests written with `pytest` to ensure the application’s reliability and stability:

- **Models**: Tests validate the creation and relationships of `Task` and `Tag` models.
- **Forms**: Tests check the `TaskForm` for field validation and input handling.
- **Views**: Covers CRUD operations for tasks and tags, ensuring expected behavior and redirects.
- **URLs**: Verifies that each URL resolves to the correct view.

Run all tests with:
```bash
pytest
```


## Page example
![list](images/TODO%20list.png)
![list](images/tags.png)