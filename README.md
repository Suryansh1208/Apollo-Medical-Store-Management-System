# Apollo-Medical-Store-Management-System

The Apollo Medical Store Management System is a Python-based application for managing a medical store's inventory and billing operations. It allows shop owners to add, display, search, and delete medicines, as well as manage customer billing.

## Features

- **Shop Owner (Admin)**:
  - Add medicines to the inventory.
  - Display a list of all medicines in stock.
  - Search for medicines by name.
  - Display medicines by company.
  - Check medicines that have expired.
  - Delete medicines from the inventory.

- **Customer (Billing)**:
  - Create bills for customers.
  - Display customer bills.
  - Search for bills by bill number.
  - Edit bill details (e.g., quantity).
  - Delete bills.

## Prerequisites

- Python 3.x
- MySQL Database

## Setup

1. Install Python if you haven't already: [Python Installation Guide](https://www.python.org/downloads/)

2. Install the MySQL connector library:

   pip install mysql-connector-python

   Create a MySQL database named Suryansh1208.

Update the host, user, password, and other database connection details in the code to match your MySQL server configuration.
python main.py
Follow the on-screen menu options for shop owner (admin) or customer (billing) operations.

## Database Tables
_medicalproject: Stores information about medicines.
customertable: Stores customer billing details.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository, create a new branch, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Suryansh Pandey






