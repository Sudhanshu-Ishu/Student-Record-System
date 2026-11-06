# Student Record Management System

A simple command-line application in Python for managing student records. Records are saved in a local JSON file, so they are still there the next time you run the program.

Built by Sudhanshu Yadav as a task for the CodeNova Python Programming internship.

## Features

- Add a student (name, age, course) with an automatically assigned ID
- View all students in a table
- Search by ID or by part of a name
- Update a student (press Enter to keep a current value)
- Delete a student, with a confirmation prompt
- Input validation (no empty fields, age must be 1-120, ID must be a number)
- Data saved to `students.json`; an unreadable data file is backed up instead of crashing the program

## Requirements

- Python 3.8 or newer
- No external libraries (standard library only)

## How to Run

```
python main.py
```

Menu options:

```
1. Add Student
2. View All Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
```

Type a number from 1 to 6 and follow the prompts.

## Example

```
--- All Students ---

ID    Name                    Age   Course
-------------------------------------------------------
1     Asha Rai                21    Python
-------------------------------------------------------
Total students: 1
```

## Data Storage

Records are stored in `students.json` in the same folder as `main.py`. The file is created the first time you add a student.

## Limitations

- Command-line only, with no graphical interface
- Stores data in a single local JSON file, so it is meant for small, personal use
