
# 📚 Library Management System

A comprehensive console-based **Library Management System** implemented in **C++** that handles book management, user accounts, borrowing/returning operations, and fine calculations.

## Features

### User Management
- Three user roles:
  - Students
  - Faculty
  - Librarians
- Registration system with password authentication.
- Role-specific privileges:
  - **Students:** Borrow up to **3 books** for **15 days**.
  - **Faculty:** Borrow up to **5 books** for **30 days**.
  - **Librarians:** Full administrative access.

### Book Operations
- Add and remove books with validation.
- Modify book details (title, author, ISBN, etc.).
- Track book status:
  - Available
  - Borrowed
  - Reserved
- Display all books in the library.

### Transaction System
- Borrow and return books with date tracking.
- Automatic fine calculation (**₹10/day** for students).
- View borrowing history and currently borrowed books.
- Fine payment system.

### Data Persistence
Save and load data using text files:
- `books.txt`
- `students.txt`
- `faculty.txt`
- `librarians.txt`
