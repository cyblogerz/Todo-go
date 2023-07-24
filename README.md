## Todo-go

Todo-go is a simple command-line todo list application written in Go. It allows you to manage your tasks by adding new tasks, marking tasks as completed, deleting tasks, and listing all the tasks.

### Installation

To install Todo-go, you need to have Go installed on your system. If you don't have Go installed, you can download it from the official Go website: https://golang.org/

Once you have Go installed, you can install Todo-go by running the following command:

```
go install github.com/cyblogerz/Todo-go/cmd/todo
```

### Usage

The application accepts various command-line flags to perform different actions. Here are the available flags:

- `-add`: Add a new todo item to the list.
- `-complete`: Mark a todo item as completed by providing the index of the task. (e.g., `todo -complete 1`)
- `-del`: Delete a todo item by providing the index of the task. (e.g., `todo -del 2`)
- `-list`: List all the todo items.

### Examples

- Add a new todo:

  ```
  todo -add "Buy groceries"
  ```

- Mark a todo as completed:

  ```
  todo -complete 1
  ```

- Delete a todo:

  ```
  todo -del 2
  ```

- List all todos:

  ```
  todo -list
  ```

- To provide input without flags, just run the `todo` command:

  ```
  todo
  ```

  The application will prompt you to enter a new todo task.


### Contributing

Contributions are welcome! If you find a bug or have an idea for an improvement, feel free to open an issue or submit a pull request on GitHub.


---
