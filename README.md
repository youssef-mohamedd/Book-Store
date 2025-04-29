# Book Store Application with Spring Boot

A simple book store management system built with Spring Boot that allows users to manage books, add them to a personal list, and perform CRUD operations.

## Features

- **Book Management**
  - Add new books to the store
  - View all available books
  - Edit existing book details
  - Remove books from the store
- **Personal Book List**
  - Add books to your personal collection
  - View your personal book list
  - Remove books from your personal list
- **User Interface**
  - Simple and intuitive web interface
  - Login page for user authentication

## Technologies Used

- **Backend**
  - Java 17
  - Spring Boot 3.x
  - Spring MVC
  - Thymeleaf (for server-side templating)
  
- **Frontend**
  - HTML
  - CSS
  - Bootstrap (for styling)

## Controllers

### BookController
Handles all book-related operations:
- `/` - Home page
- `/book_register` - Book registration form
- `/available_book` - Displays all available books
- `/my_books` - Displays user's personal book list
- `/save` - Saves a new book
- `/edit/{id}` - Edits an existing book
- `/deleteBook/{id}` - Deletes a book from store
- `/myList/{id}` - Adds book to personal list
- `/deleteMyBook/{id}` - Removes book from personal list

### LoginController
Handles authentication:
- `/showLoginPage` - Displays login page
