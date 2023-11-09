# JavaLab2
## Library Management System
This Java project implements a simple Library Management System with support for managing books, DVDs, patrons, and their interactions. The system allows adding and removing items, registering patrons, lending and returning items, and listing available and borrowed items.

### Project Structure
The project consists of the following classes:

Item (Abstract Class): Represents the common attributes and methods for items in the library.
Book and DVD (implement Item): Concrete classes representing specific types of items in the library.
Patron: Represents a library patron with a name, ID, and a list of borrowed items.
IManageable (Interface): Defines methods for managing items in the library.
Library (implements IManageable): Implements the library management system, including item and patron registration, lending, returning, and listing.
### Usage
Create items using the Book and DVD classes.
Register patrons using the Patron class.
Use the Library class to add items, remove items, register patrons, lend items, return items, and list available and borrowed items.
