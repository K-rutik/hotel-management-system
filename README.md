# hotel-management-system
in this repository you will find resturant bill management code 
The given code is a simple restaurant billing system implemented in C language using file handling to store customer orders. It contains three structures, items, orders, and order, which are used to store item details, order details, and order history, respectively.

The generateBillHeader() function is used to generate the header part of the bill, including the name of the restaurant, date, and customer name. The generateBillBody() function is used to generate the body part of the bill, which includes the item name, quantity, and price. The generateBillFooter() function is used to generate the footer part of the bill, including the sub-total, discount, net total, CGST, SGST, and grand total.

The main() function provides a dashboard to the user to perform various operations, including generating a new invoice, displaying all invoices, searching for a specific invoice, and exiting the program. It uses a switch-case statement to handle different options selected by the user.

When the user selects option 1, the program asks for the customer name, date, number of items, and item details. It then calls the generateBillHeader(), generateBillBody(), and generateBillFooter() functions to generate the bill and saves the order details to a binary file named "RestaurantBill.dat".

When the user selects option 2, the program reads all the orders from the "RestaurantBill.dat" file and displays them using the generateBillHeader(), generateBillBody(), and generateBillFooter() functions.

When the user selects option 3, the program asks for the name of the customer and searches for the order in the "RestaurantBill.dat" file. If the order is found, it displays the bill using the generateBillHeader(), generateBillBody(), and generateBillFooter() functions.

Overall, the code provides a simple implementation of a restaurant billing system that can be useful for small restaurants. However, it can be improved by adding more features such as the ability to modify and delete orders, print bills in different formats, and handle errors more gracefully.
