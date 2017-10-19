# Lab - React Todo List

## Objectives
  * Apply event listeners in React.
  * Understand the distinction between state and props in React.
  * Change state of react components.
  * Capture user input using refs on elements.
  * Modify the top-level state of a component from a lower-level component.

## Setup Instructions

1. Create react application
  ```sh
  create-react-app lab--react-todo-list
  ```

2. After installation completes, start the task runner and local webserver:
  ```
  npm start
  ```

3. Build the project per requirements.


## Normal Mode

  - add a new task and see it appear in a list of pending tasks.
  - remove a task from the list.
  - [live demo of normal mode](https://arcane-wildwood-43309.herokuapp.com/#normal-mode)

## Explorer Mode

  - add additional information about a task, such as its urgency status and due date.
  - you will need to use `<input type="date"/>` and `<input type="checkbox">` to capture this information
  - [live demo of explorer mode](https://arcane-wildwood-43309.herokuapp.com/#explorer-mode)


## Adventure Mode

Instead of simply removing a completed task, a user should be able to toggle that task's completion status.

A hint on implementation:

  - When one of your low-level UI components (e.g., TodoItem) receives user input to change a task from undone to done or vice versa, it needs to notify the top-level, "smart" component, so that that component can re-set its state.


  - [live demo of adventure mode](https://arcane-wildwood-43309.herokuapp.com/#adventure-mode)
