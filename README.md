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


## Postman Testing

Our project includes comprehensive testing through Postman for key CRUD operations. These tests ensure that the API behaves as expected:

- **Create Tag**: Verifies successful tag creation with CSRF handling.
- **Update Tag**: Checks that tags can be updated and return correct responses.
- **Delete Tag**: Confirms tags are deleted successfully.
- **Create Task**: Tests task creation with required fields, including tags.

Each request has assertions for status codes and response validation to ensure API functionality.


## JMeter Performance Testing

The project includes performance tests using JMeter to evaluate API responsiveness under load. Key operations covered:

- **Task and Tag Creation**: Assesses server performance during high-volume record creation.
- **Fetching Tasks and Tags**: Measures response times with heavy read request loads.
- **Update and Delete Operations**: Tests stability during simultaneous data modification requests.

Scripts are saved in `.jmx` format and can be reused for future performance testing.


## Selenium Testing

The project includes automated testing for key features using Selenium:

- **Creating a Task**: Tests the functionality for adding a new task, setting task content, selecting the date, and marking completion status.
- **Updating a Task**: Allows updating existing tasks, including content, date, and completion status.
- **Deleting a Task**: Confirms the ability to delete a task through a confirmation dialog.



## Page example
![list](images/TODO%20list.png)
![list](images/tags.png)