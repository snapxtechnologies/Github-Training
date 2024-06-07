# To-Do List Application

This is a simple command-line To-Do List application written in Python. It allows you to add, remove, and view tasks.

## Features

- Add new tasks
- Remove existing tasks
- View all tasks

## Requirements

- Python 3.x

## Usage

1. Clone the repository (after you initialize it on GitHub):
    ```sh
    git clone https://github.com/yourusername/todo_app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd todo_app
    ```
3. Run the application:
    ```sh
    python todo.py
    ```


## Git Training Details

### Step 1: Initialize a Git Repository

1. Open a terminal and navigate to your project directory:
    ```sh
    cd path/to/todo_app
    ```
2. Initialize a new Git repository:
    ```sh
    git init
    ```

### Step 2: Create a `.gitignore` File

Create a `.gitignore` file to exclude unnecessary files from the repository. Add the following content:


### Step 3: Commit the Initial Code

1. Add the files to the staging area:
    ```sh
    git add .
    ```
2. Commit the files:
    ```sh
    git commit -m "Initial commit: Add to-do list application"
    ```

### Step 4: Practice Making Changes and Using Git

1. Add a new feature, e.g., mark tasks as complete.
2. Create a new branch for the feature:
    ```sh
    git checkout -b add-complete-feature
    ```
3. Implement the feature in `todo.py`.
4. Stage and commit the changes:
    ```sh
    git add todo.py
    git commit -m "Add feature to mark tasks as complete"
    ```
5. Merge the feature branch back into the main branch:
    ```sh
    git checkout main
    git merge add-complete-feature
    ```

### Additional Git Commands

- To view the commit history:
    ```sh
    git log
    ```
- To check the status of your repository:
    ```sh
    git status
    ```
- To view changes in your files:
    ```sh
    git diff
    ```

## License

This project is licensed under the MIT License.
