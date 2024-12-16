Library Management System (LMS)
 Overview = The Library Management System (LMS) is an application designed to manage and streamline various operations in a library. 
            The system facilitates user interaction with the library’s catalog, enabling efficient management of books, issuing and returning of books, 
            and searching for books.
            Administrators can perform tasks such as adding, editing, and deleting books while maintaining records of available copies. 
            This application reduces manual effort, improves efficiency, and enhances the library’s operations.
            Adding new books.
            Editing or deleting book records.
            Issuing books to users.
            Returning issued books.
            Searching for books in the library catalog
			      Available copies for each book 
 Project Phases
               The project will be divided into two main phases:
           Phase One:
               Focus on teacher-specific functionalities.
               Implement validation to ensure accurate data entry.
           Phase Two:
               Expand features for broader user groups.
               Enhance reporting and tracking capabilities.			
 Key Features
           Book Management:
                 Add, edit, and delete book records.
                 Maintain details like title, author, ISBN, published year, and quantity.
           Issue/Return Books:
                 Manage book issuance and returns.
                 Automatically update the available quantity of books.
           Search Functionality:
                 Search for books using criteria such as title, author, or ISBN.
           Transaction Tracking:
                 Maintain records of issued books, including book ID, user ID, issue date, and return date.
           Book Availability:
                 Display the current available quantity of each book.
Database Design
                The application will utilize a MySQL database for managing data efficiently. 
			           Below are the primary tables and their relationships:			
			  Books Table:
                Stores information about books, including ID, title, author, ISBN, published year, and quantity.
        Transactions Table:
               Stores records of issued and returned books, including book ID, user ID, issue date, and return date.
			 User Table
			 
