# Library Management System


This is a simple Library Management System developed in Java. It allows users to manage books and students in a library, including adding new books, searching for books, checking in and checking out books, and registering students.

**Features**
- Add Books: Add new books to the library.
- Search Books: Search for books by serial number or author name.
- Upgrade Book Quantity: Update the quantity of existing books.
- Display All Books: Show all the books available in the library.
- Register Students: Register new students.
- Display All Students: Show all registered students.
- Check Out Books: Allow students to check out books.
- Check In Books: Allow students to return books.
  

**File Structure**
- book.java: Defines the book class, which includes details like serial number, book name, author name, and quantity of books.
- books.java: Manages book-related operations such as adding, searching, and updating books.
- student.java: Defines the student class, which includes student details and the books borrowed by the student.
- students.java: Manages student-related operations such as adding students, checking out, and checking in books.
- library.java: Contains the main class Library, which provides a menu for interacting with the library system.

  
How to Run

- Clone the repository:

'''sh

git clone https://github.com/your-username/library-management-system.git
cd library-management-system


- Compile the Java files:

'''sh

javac -d . book.java books.java student.java students.java library.java


- Run the application:

'''sh

java Library.Library


- Usage
Upon running the application, you will be presented with a menu to select various operations. Follow the prompts to add books, search for books, register students, and manage book checkouts and check-ins.

'''sh

********************Welcome to the GFG Library!********************
                 Select From The Following Options:             
**********************************************************************
Press 1 to Add new Book.
Press 0 to Exit Application.
Press 2 to Upgrade Quantity of a Book.
Press 3 to Search a Book.
Press 4 to Show All Books.
Press 5 to Register Student.
Press 6 to Show All Registered Students.
Press 7 to Check Out Book.
Press 8 to Check In Book
