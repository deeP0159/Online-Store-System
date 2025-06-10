Simple Order Management System (C++)

📋 Description

This is a simple C++ application that simulates a basic order management system. It demonstrates the use of object-oriented programming (OOP) concepts such as classes, encapsulation, and STL containers (map, vector, pair). The program allows you to:

Manage a catalog of products.
Create and display customer orders.
Calculate the total bill based on product prices and quantities.
Update and display stock levels after processing an order.
🛠️ Features

Product Class: Stores product information like ID, name, category, and price.
Order Class: Stores order details including customer ID, order date, and a list of purchased products.
Stock Management: Keeps track of product inventory and updates stock levels after each order.
Total Calculation: Calculates the total bill amount based on ordered items and their quantities.
Formatted Output: Displays a neatly formatted product catalog, order summary, and stock status.
🧾 Sample Output

Available Products:
ProductID: 101, Name: Laptop, Category: Electronics, Price: $1000
ProductID: 102, Name: SmartPhone, Category: Electronics, Price: $800
ProductID: 103, Name: Coffee Maker, Category: Kitchen, Price: $150
ProductID: 104, Name: Blender, Category: Kitchen, Price: $200
ProductID: 105, Name: Desk Lamp, Category: Home, Price: $50

Order Summary:
OrderID: 1, CustomerID: C001, OrderDate: Mon Jun 10 09:00:00 2025
Items in Order:
ProductID: 101, Name: Laptop, Quantity: 2, Price: $1000, Subtotal: $2000
ProductID: 103, Name: Coffee Maker, Quantity: 1, Price: $150, Subtotal: $150
Total Bill: $2150

Updated Stock Levels:
ProductID: 101, Stock: 8
ProductID: 102, Stock: 20
ProductID: 103, Stock: 14
ProductID: 104, Stock: 5
ProductID: 105, Stock: 7
📂 Code Structure

Product class: Handles individual product details.
Order class: Handles customer order information.
main() function:
Initializes product catalog and stock.
Creates and displays a customer order.
Updates stock after processing the order.
💻 Technologies Used

C++11 or later
Standard Template Library (STL)
🚀 How to Run

Copy the source code into a file named main.cpp.
Compile using a C++ compiler:
g++ -std=c++11 -o orderSystem main.cpp
Run the executable:
./orderSystem
✅ Use Cases

Learning OOP principles in C++
Practicing use of STL containers
Simulating a real-world ordering system
📬 Contact

For feedback or queries, feel free to connect!
