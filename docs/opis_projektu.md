==================================================
# PROJECT: Task Tracker
==================================================

## DESCRIPTION
-----------
**Task Tracker is a simple command-line application written in Python.
It allows users to add, view, mark as complete, and delete tasks.
All tasks are stored locally in a text file so they persist between runs.**

This project is intended as a beginner-friendly example of:
- File I/O
- Basic data structures
- Command-line interaction
- Program organization

--------------------------------------------------

## FEATURES
--------
1. Add a new task
2. View all tasks
3. Mark a task as completed
4. Delete a task
5. Save tasks to a local file (tasks.txt)

--------------------------------------------------

## PROJECT STRUCTURE
-----------------
task_tracker/
│
├── task_tracker.py   -> Main application file
├── tasks.txt         -> Stores tasks
└── README.txt        -> Project documentation

--------------------------------------------------

## HOW IT WORKS
------------
1. The program starts and loads existing tasks from tasks.txt.
2. A menu is displayed to the user.
3. The user selects an option by entering a number.
4. Based on the option:
   - Tasks can be added, viewed, updated, or removed.
5. Changes are saved automatically to tasks.txt.

--------------------------------------------------

## TASK FORMAT
-----------
Each task is stored in the following format:

[STATUS]|[TASK_DESCRIPTION]

Example:
PENDING|Buy groceries
DONE|Finish homework

--------------------------------------------------

## REQUIREMENTS
------------
- Python 3.8 or higher
- No external libraries required

--------------------------------------------------

## HOW TO RUN
----------
1. Open a terminal
2. Navigate to the project directory
3. Run the following command:

   *python task_tracker.py*

--------------------------------------------------

## POSSIBLE IMPROVEMENTS
---------------------
- Add due dates for tasks
- Add task priorities
- Support categories
- Create a graphical
