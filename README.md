# Library System

This project is a simple console-based library management system. It allows the admin to add books, search for books, add users, borrow and return books, and retrieve information about borrowed books.

## Table of Contents

**- [Features](#features)**<br/>
**- [Getting Started](#Getting Started)**<br/>
**- [Usage](#usage)**<br/>
**- [Contributing](#contributing)**<br/>

## Features

-[x] Add books: The admin can add books to the library system by providing the book's ID, name, and total quantity.
-[x] Search for books: The admin can search for books by entering a book name prefix. The system will return a list of books whose names match the given prefix.
-[x] List all books: The admin can print a list of all books in the library system.
-[x] List users who borrowed a book: The admin can enter a book name and retrieve a list of users who have borrowed that book.
-[x] Add users: The admin can add users to the library system by providing the user's ID and name.
-[x] Borrow books: Users can borrow books from the library system. The system checks the availability of the book and updates the quantity if the book is available.
-[x] Return books: Users can return books they have borrowed. The system marks the book as returned and increments the quantity.

## Getting Started

To run the library management system, follow these steps:

1. Clone the repository: <br/>
`git clone https://github.com/AhmedHamdi0/library-management-system.git`
2. Navigate to the project directory: <br/>
`cd library-management-system`
3. Run the program: <br/>
`python library_management.py`

## Usage

Upon running the program, you will be presented with a menu of options. Choose the desired operation by entering the corresponding number:

**1. Add book:** Add a new book to the library system.<br/>
**2. Print library books:** Display a list of all books in the library.<br/>
**3. Print books by prefix:** Search for books by entering a name prefix.<br/>
**4. Add user:** Add a new user to the library system.<br/>
**5. Borrow book:** Borrow a book from the library.<br/>
**6. Return book:** Return a borrowed book.<br/>
**7. Print users borrowed book:** Retrieve a list of users who have borrowed a specific book.<br/>
**8. Print users:** Display a list of all users in the library system.<br/>
**9. Exit:** Exit the program.<br/>

## Contributing

Contributions to the Hospital Management System are welcome! If you find any issues or want to enhance the system with new features, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b my-new-feature`.
3. Make changes and commit them: `git commit -am 'Add new feature'`.
4. Push the branch: `git push origin my-new-feature`.
5. Submit a pull request.
