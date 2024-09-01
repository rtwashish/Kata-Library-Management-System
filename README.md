Library Management System Kata
Objective
This project implements a simple Library Management System that allows users to perform basic operations like adding books, borrowing books, returning books, and viewing available books. The focus is on clean coding practices, Test-Driven Development (TDD), and adherence to SOLID principles.
Features
1. Add Books
•	Users can add new books to the library.
•	Each book has a unique identifier (ISBN), title, author, and publication year.
2. Borrow Books
•	Users can borrow books from the library.
•	The system checks if the book is available before allowing it to be borrowed.
•	If the book is unavailable, the system raises an appropriate error.
3. Return Books
•	Users can return borrowed books.
•	The system updates the availability status of the book accordingly.
4. View Available Books
•	Users can view a list of all available books in the library.
Installation
1.	Clone the repository:
git clone https://github.com/rtwashish/Kata-Library-Management-System/tree/main
2.	Navigate to the project directory:
cd library-management-system-kata
3.	Compile the project using your preferred Java IDE or via the command line:
javac -d bin src/in/sp/backend/*.java
4.	Run the application:
java -cp bin in.sp.backend.LibraryManagementSystem


Usage
•	The application will present a menu with options to add, borrow, return, or view books.
•	Follow the prompts to interact with the system.
Test-Driven Development (TDD)
This project follows TDD practices. The tests are written before the implementation of the functionality. The three laws of TDD have been followed:
1.	You are not allowed to write any production code unless it is to make a failing unit test pass.
2.	You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
3.	You are not allowed to write any more production code than is sufficient to pass the one failing unit test.
The project aims for high test coverage with meaningful test cases.
Contributions
Contributions are welcome! If you have suggestions for improvements or new features, please create an issue or submit a pull request.
License
This project is licensed under the MIT License.
