# Flutter Login Project

This is a Flutter project that implements a login functionality with email and password validation.

## Requirements

- The email address must match the format: WWW.DDDD@izam.co, where each 'W' stands for a character between a-z (either capital or lowercase), and each 'D' stands for a number 0-9.
- The password must have a minimum length of 8 characters and contain at least 1 number and one of the following symbols: (!$#^*).

## Behavior

- Each time a user logs in with a valid email and password, the login information is stored in a SQLite database.
- The database keeps track of how many times the user has logged in with the same email and password pair.
- Upon successful login, the user receives a success message indicating the number of times they have used the email and password pair to log in.

## Database Structure

The SQLite database table structure for storing login records is as follows:

| Column        | Type    |
|---------------|---------|
| email         | TEXT    |
| password      | TEXT    |
| login_count   | INTEGER |

## Getting Started

1. Clone the repository:
2. Install dependencies:
3. Run the application:

Feel free to explore the code and make any necessary modifications.

For more information, refer to the documentation and source code files.

## Contributors

(https://github.com/mohamednosier)
```

Make sure to replace "your-username" with your actual GitHub username and customize the "Contributors" section with the names and GitHub profiles of the project contributors.

This README file will provide an overview of the login project, its requirements, behavior, and database structure. It also includes instructions for getting started with the project and acknowledges the contributors.
