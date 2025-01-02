Library System Project in Zoho Creator
Overview
This is a Library Management System developed using Zoho Creator to handle the management of books, members, staff, transactions, and related operations. The system supports features like issuing and returning books, managing fines for overdue books, tracking books by genre, and role-based permissions for staff members.

Features
1. Modules:
Books Module: Manages book records with fields such as Book ID, Title, Author, Genre, Publication Year, Available Copies, ISBN Number, and Rating.
Members Module: Handles member details, including Member ID, Name, Email, Phone Number, Membership Start Date, Membership Type, and Max Books Allowed.
Transactions Module: Tracks book borrowings and returns, including Transaction ID, Member, Book, Issue Date, Return Date, Status, and Fine Amount.
Staff Members Module: Manages staff details with Staff ID, Name, Email, Role, and Phone Number.
2. Key Functionalities:
Form Validations: Ensures unique ISBN numbers, valid publication year, and prevents duplicate member emails.
Workflows: Automates tasks like decreasing available copies when a book is issued, increasing them when returned, and calculating fines for overdue books.
Reports & Dashboards: Generates reports such as overdue books and top members, and provides visualizations like genre popularity charts.
Role-Based Permissions: Librarians can issue and return books, while assistants can only view book and member details.
3. Additional Features:
Book as Featured: Mark books as featured and highlight them in reports.
Mark Book as Lost: A custom action to mark a book as lost, setting available copies to 0.
How to Use
1. Setting Up the Application in Zoho Creator:
Log in to Zoho Creator.
Create a new application or import the .ds file provided (download from the repository).
Set up the necessary modules as described in the Modules section.
Implement workflows for automation, such as updating available copies on book issue/return and calculating fines for overdue books.
2. Creating Reports and Dashboards:
Create custom reports for overdue books and top members.
Use dashboards to visualize data, including genre popularity charts and staff activity logs.
3. Role-Based Permissions:
Set permissions for Librarians and Assistants within the Staff Members Module:
Librarians: Can issue and return books.
Assistants: Can only view books and members.
Testing the Application
To test the functionality of the system:

Import dummy data for Books, Members, and Transactions using CSV files.
Test the workflows, ensuring that available copies decrease and increase correctly, and that fines are calculated accurately.
Verify the reports to ensure that overdue books are tracked and the top members report displays accurately.
Requirements
Zoho Creator account (required to import and use the .ds file).
Access to the necessary modules and workflows in Zoho Creator.
Files Provided
.ds file (Zoho Creator export file) to import the application directly into Zoho Creator.
CSV files (optional): For importing sample data into the modules.
Future Enhancements
Online Reservation: Implement functionality to allow members to reserve books.
Fine Payment Integration: Integrate with payment gateways for fine payments.
Reporting Enhancements: Add additional reports like book popularity by genre and member borrowing trends.

Acknowledgements
Zoho Creator for providing a powerful low-code platform to build this library management system.
GitHub for hosting this project.
