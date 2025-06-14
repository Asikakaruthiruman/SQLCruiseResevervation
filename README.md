This project is a Cruise Reservation System built using Python and MySQL, designed to simulate a hotel-like cruise management application. It handles everything from customer check-ins, room booking, restaurant ordering, fashion store purchases, gaming charges, to total bill generation, all stored in a MySQL database.

Features:
MySQL connectivity and database creation
Customer registration and detail management
Room selection with dynamic rent calculation
Restaurant billing based on menu choices
Gaming and fashion store billing modules
Comprehensive final billing and reporting
Customer search and billing history

Tech Stack:
Python 3
MySQL (via mysql-connector-python)
Command-line interface (CLI)

Key Modules:
MYSQLconnectionCheck() – Validates and initializes DB connection
userEntry() – Collects and stores customer data
roomRent(), Restaurent(), Gaming(), Fashion() – Feature-specific billing systems
totalAmount() – Calculates final bill and generates a receipt
searchCustomer() & searchOldBill() – Lookup modules
