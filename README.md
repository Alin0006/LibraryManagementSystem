Library Management System – Java GUI Project

Developed as a standalone desktop application using Java Swing.

Overview:
This mini-project simulates the key functionalities of a library management system, including user registration, login, book lending, and return processes. It is designed with a modern and intuitive interface.

Features:
- User Registration with email validation and username availability check
- Login system with file-based credential verification
- Main Dashboard with stylised navigation and icon-based buttons
- View books by category (10 titles per category)
- Book lending form with dropdowns, calendar selectors, and auto-approval
- Book return system with user search and return confirmation
- Real-time integration with local storage using `.txt` files
- Borrowed books recorded in the system and reflected in reports
- Graphical reports interface for borrowed books
- Smooth navigation between all screens
- Designed with a modern visual theme (rounded corners, custom icons, warm colours)

File Storage:
- `accounts.txt` – Stores login credentials (username, password)
- `users.txt` – Stores user profiles (userID, full name, email)
- `borrowed_books.txt` – Stores lending information
- `returned_books.txt` – Stores returned book data (if implemented)
- Other temporary/form data stored in respective `.txt` files

Special Note:
The “Manage Books” feature is currently inactive. The screen is intentionally designed as a placeholder for future development.

Default Users (for testing):
- Username: `alin1`
- Password: `alin1`

Java Version: JDK 21  
IDE: IntelliJ IDEA Community Edition / NetBeans (compatible)  
Dependencies: None (pure Java Swing)

Author: Alin Dragomir  
Version: 1.0  
Last updated: 27/06/2025
