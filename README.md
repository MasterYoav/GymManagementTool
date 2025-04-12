GymManagementTool

A Python-based Gym Management Tool developed as part of an Object-Oriented Programming (OOP) assignment.
This application facilitates the management of gym members, trainers, and classes through a command-line interface.

Features

- Member Management: Add, update, and remove gym members.
- Trainer Management: Manage trainer profiles and assign them to classes.
- Class Scheduling: Schedule new classes, enroll members, assign trainers.
- Reporting: Generate summaries on class attendance and membership status.
- Persistent Storage: Saves all data in local JSON files for reuse across sessions.

Installation

1. Clone the repository:

   git clone https://github.com/MasterYoav/GymManagementTool.git
   cd GymManagementTool

2. Run the application:

   python main.py

   (Requires Python 3.x)

Usage

Once you run main.py, the application launches in the terminal/command-line.
You will be prompted to choose options such as:

- Add/Edit/Delete a Member
- Create/Edit/Delete a Trainer
- Schedule or manage Classes
- Print attendance or registration Reports

The application stores data in the data/ directory using JSON format.

Project Structure

GymManagementTool/
├── main.py                 # Entry point of the application
├── member.py               # Defines the Member class and logic
├── trainer.py              # Trainer class and logic
├── class_schedule.py       # Handles class scheduling
├── utils/
│   └── helpers.py          # Utility functions for data handling
├── data/
│   ├── members.json        # Stores member records
│   ├── trainers.json       # Stores trainer records
│   └── classes.json        # Stores class schedules
└── README.md               # This file

License

This project is licensed under the MIT License.

Author

Developed by Yoav Peretz
B.Sc. Computer Science
Course: Object-Oriented Programming (OOP)
