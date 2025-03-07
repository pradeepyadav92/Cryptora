# Cryptora
This is a Cryptora program written in Python. It allows users to securely store, retrieve, and manage their passwords for different services. The program includes functionalities for user authentication (signup and login) and password management.

Features:
User Authentication:

Users can sign up by creating a username and password.
Users can log in with their registered credentials.
Passwords are securely stored using SHA-256 hashing.
Password Management:

Add Password: Users can save credentials for different services.
Retrieve Password: Users can look up stored credentials.
Delete Password: Users can remove stored credentials.
Show All Passwords: Users can view all stored credentials.
File-Based Storage:

User data is stored in users.json (hashed passwords).
Passwords are stored in data.json.
Workflow:
User Authentication: The program starts by asking users to log in or sign up.
Password Management: After logging in, users can add, retrieve, delete, or view passwords.
