Project 3												

Project Name: Library Management System

Description:
You are required to develop a program that adds, deletes, updates and displays books to and from the library management system. This program is expected to help the library in keeping track of the books. Use Vector to store all the information about the books, rented books and archived books. You are free to use multiple vectors. (Note: You can use file processing if you like instead of Vectors but we have not covered that in this course).

Requirements:
Below are bare minimum requirements for this project, however, you are free to add more features to your project:

•	There is a “Books” vector which contains book details like Book name, Author Name, Publisher, Year Published and etc.
•	There is a “RentedBooks” vector which contains Books that have been rented and have details like Book Name, Borrowed Person Name, Date Rented, Return Date and etc.
•	There is a “Archived” vector which contains details like Book name, Author Name, Publisher, Year Published and etc.
•	There should be one method for adding new book : “addBook” which will add new Book to the Books vector.
•	There should be one method for searching the book : “searchBook” which will search the Book in the Books vector.
•	There should be one method for renting a book: “RentBook” which will call the searchBook method first to see if that book is available and if available the book is added to the RentedBooks vector.
•	Finally, your program should be able to provide the delete ability for deleting the books from Books, RentedBooks and Archived vector.
Your program should show a menu as below:
1.	Add a new Book
2.	Rent a Book
3.	Archive a Book
4.	Search a Book (in Books, RentedBooks and Archives)
5.	Delete a Book (from Books, RentedBooks and Archives)
6.	Display a Book (from Books, RentedBooks and Archives)
7.	Update a Book (from Books, RentedBooks and Archives)
8.	Exit
