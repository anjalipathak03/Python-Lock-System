# Python-Lock-System

# Lock System

This is a simple lock system implemented in Python. It allows you to set a password and lock/unlock the system using the password.

## Getting Started

To use this lock system, follow these steps:

1. Ensure you have Python installed on your system. This code is compatible with Python 3.

2. Download or clone the project repository to your local machine.

3. Open the `lock_system.py` file in a Python IDE or text editor.

4. Set the desired password by modifying the `password` parameter when creating the `LockSystem` object.

5. Run the `lock_system.py` file to execute the code.

## Usage

The lock system provides the following methods:

- `LockSystem(password)`: Creates a new lock system with the specified password.

- `unlock(password_attempt)`: Attempts to unlock the lock system using the provided password attempt. If the attempt matches the password, the system is unlocked. Otherwise, an incorrect password message is displayed.

- `lock()`: Locks the system, preventing further access until unlocked.

- `is_locked()`: Returns `True` if the system is currently locked, or `False` if it is unlocked.

You can customize the example usage provided in the code to suit your needs. Feel free to modify, expand, or enhance the functionality of the lock system.


