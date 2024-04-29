# Task Management System

## Project Overview

The Task Management System is a console-based C program designed to manage tasks through a menu-driven interface. It supports the following functionalities:

- Add tasks with due dates
- Edit existing tasks
- Mark tasks as completed
- Delete tasks
- View tasks (remaining, completed, or both)
- Sort tasks by various criteria
- Export tasks to CSV
- Clear all tasks
- Exit the program

## Features

- **Linked List Data Structure**: Tasks are stored in a linked list for flexible management.
- **Dynamic Task Management**: Users can add, edit, delete, and mark tasks as done.
- **Sorting and Exporting**: Sort tasks by different criteria and export them to CSV.

## Setup Instructions

### Prerequisites:

- C Compiler (e.g., GCC, MinGW)
- Visual Studio Code or similar IDE (optional)

### Clone or Download the Project:

- Clone the repository using `git clone <repository-url>`, or download the ZIP file from the repository and extract it.

### Compile the C Code:

- If you're using GCC or MinGW, open a terminal in the project folder and run:
  ```
  gcc -o Task_Manager Task_Manager.c
  ```
  This command compiles the C code and creates an executable named Task_Manager.

### Run the Compiled Program:

- Once compiled, you can run the program with:
  ```
  ./Task_Manager
  ```

## Usage Instructions

### Launch the Program:

- Open a terminal and navigate to the project folder.
- Run `./Task_Manager` to start the program.

### Use the Menu:

- Follow the on-screen prompts to interact with the program.
- Select an option from the menu to perform various tasks.

### Example Interaction

Here's an example of typical usage:

- **Add Tasks**: Choose option 1, then enter task details, including name and due date.
- **Mark a Task as Done**: Choose option 3, then enter the task's serial number to mark it as completed.
- **Delete a Task**: Choose option 4, then enter the task's serial number to delete it.

## Troubleshooting

If you encounter errors or issues, check the following:

- **Compiler Warnings**: Ensure that all compiler warnings are addressed. Correct implicit declarations and escape sequence errors.
- **Memory Management**: Verify that memory is properly allocated and deallocated to avoid memory leaks.

## Contributing

If you'd like to contribute to this project, please submit a pull request with your changes or create an issue to discuss proposed changes.

## Contact

If you have any questions or need additional assistance, please contact the project owner at `<b22mt031@iitj.ac.in>`.

## License

This README template provides a comprehensive guide to your project, including setup, usage, and troubleshooting. You can customize the content based on your specific project details and requirements.
