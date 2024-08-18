# **Book-Shop-System**
A simple bookshop system with file management designed to handle essential bookstore operations, using txt files to store and manage data by C++ programming language.


## **Functions**  
1. CustomerToStruct function:
 Reads customers data from Customer File into Customers struct.
2. booksToStruct function:
 Reads books data from Book File into Books struct.
3. orderToStruct function:
 Reads orders data from order File into Order struct.
4. search_books function:
 used to search for books by writing the title, catogry or author name of book.
5. signUp function:
 Asks the new user to enter his username, password, email, home address and phone number. It also assigns the user a new ID and writes his data to allCustomers struct array and then to the Customers file.
6. login function:
 Receives username and password from existing customer and checks if they are the same as the data stored in the allCustomers array.
7. customersData function:
 Erases all existing data in the file and writes everything stored in allCustomers array to file.
8. editInformation function:
 Asks customer what piece of personal information he would like to change ans receives new data from him. If it isn't the same as what is already stored in allCustomers, it stores the new value and saves changes to file using customeraData().
9. editedBooks function:
 Erases all existing data in the file and writes everything stored in sb (books) array to file. Used when a new order is added, in order to decrease quantity in file after it is decreased in the struct array.
10. showorderreceipt function:
 Loops backwards over the orders struct array to display the very last order the customer has placed and breaks, that is if he placed any.
11. showAllOrders function:
 Loops over the orders struct array to display all orders the customers has placed, if any were placed.
12. add_order function:
 If the book’s quantity of stock not equal zero the customer will add number of books he wants and the book’s ids and the data (customer id & order date (current date) & ship date (3 days after order date) &the books ids) and then it’ll call order function to save this data in order file.
13. order function:
 this function write array of struct of orders in Order file.
