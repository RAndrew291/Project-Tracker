# ABC Project Tracker

## Overview
ABC Project Tracker is a C program that helps track and manage project milestones. It allows users to enter project details, update milestones, and determine whether the project is completed on budget and on time.

## Files in the Project
- **main.c**: The main entry point of the program.
- **definitions.c**: Contains function implementations for project tracking.
- **a1_data_structures.h**: Defines the `milestone_t` structure.
- **a1_functions.h**: Declares the functions used in the project.

## Compilation Instructions
To compile the program using GCC, run the following command:
```sh
gcc main.c definitions.c -o project_tracker
```

## Usage
1. Run the compiled program:
   ```sh
   ./project_tracker
   ```
2. Enter the total project's budget.
3. Enter the total project's duration in weeks.
4. The program calculates and displays the planned number of employees.
5. The program initializes and displays the project milestones.
6. The user can update milestone details, including time, employees, and completion status.
7. The program determines if the project stays within budget.

## Functionality
- **`dashed_line(n)`**: Prints `n` dashes.
- **`get_input_f()`**: Gets a positive float input from the user.
- **`get_input_usi()`**: Gets a positive integer input from the user.
- **`milestone_complete_input()`**: Gets a Yes/No input for milestone completion.
- **`finish_milestone_input()`**: Gets a Yes/No input for finishing remaining milestones.
- **`number_of_employees()`**: Calculates required employees based on cost and time.
- **`init_milestone()`**: Initializes milestone names and assigned budgets.
- **`milestone_updates()`**: Allows users to view and update milestones.
- **`print_menu()`**: Displays available milestones.
- **`print_stats()`**: Displays milestone details.
- **`update_stats()`**: Updates milestone statistics.
- **`check_project_completion()`**: Checks if all milestones are completed and summarizes project performance.

## Example Run
```
Welcome to ABC Project Tracker
Enter total project's Budget: 50000
Enter total project's duration in weeks: 20
The planned number of employees needed is: 25

Which milestone do you want to update? (0 to exit):
1. Technical requirements
2. System Design
3. Software Development
4. Testing
5. Product release

Your choice is: 1
```

## Author
Andrew Roberts

