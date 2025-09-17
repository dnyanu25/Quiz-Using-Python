
# QuizVS 

**QuizVS** is a Python-based quiz application that supports administrative and user functionalities. It uses SQLite for data storage and provides a basic command-line interface for interacting with quiz data.

## Features

- Admin and user login functionalities
- Create, edit, and manage quiz questions (admin)
- Attempt quizzes and view scores (user)
- Persistent data storage using SQLite

## Project Structure

```
QuizVS/
├── adminfun.py        # Admin-specific functions
├── userfun.py         # User-specific functions
├── main.py            # Entry point of the application
├── sqlcon.py          # SQLite connection utility
├── Quiz.db            # SQLite database file
├── Quiz.sqbpro        # SQLite project file (optional)
└── __pycache__/       # Compiled Python bytecode (auto-generated)
```

## Requirements

- Python 3.10 or higher
- SQLite3 (bundled with Python's standard library)

## Setup

1. Clone or extract the repository.
2. Navigate to the `QuizVS` directory.
3. Ensure the `Quiz.db` file is in place (included in the repo).

## Running the Application

```bash
python main.py
```

Follow the on-screen instructions to login as an admin or user and begin interacting with the quiz system.

## Notes

- This project is a command-line tool, so it runs in the terminal or console.
- Make sure you have Python installed and added to your system's PATH.

## License

This project is for educational purposes. Add a license if you intend to distribute or use it commercially.

---
