# ChatApp User Authentication
This project is a simple user authentication system built using Java. It includes features for user registration, password validation, and login functionality, with unit tests to verify the correctness of these features. The project is designed for learning purposes and is suitable for beginners

## Features
User Registration: Allows a user to register with a username, password, and phone number.
Username Validation: Ensures the username is correctly formatted (length ≤ 5 and contains an underscore).
Password Validation: Enforces password complexity requirements (at least 8 characters, one uppercase letter, one digit, and one special character).
Phone Number Validation: Checks if the phone number starts with +27 and is exactly 12 characters long.
Login: Allows a registered user to log in using their username and password.

# Test Cases
The following test cases are covered in the project:
## Username Validation
Valid username (contains an underscore and has a length ≤ 5)
Invalid username (no underscore)
Invalid username (length > 5)
