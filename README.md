# Car Rental System

## Overview
This is a *Car Rental System* implemented in *C++ with MySQL*, designed to manage car rentals efficiently. It allows users to book cars, manage customer data, and track rental history using a database.

## Features
- *Car Booking:* Users can rent cars based on availability.  
- *Customer Management:* Stores customer details securely.  
- *Rental Tracking:* Logs rental history for better management.  
- *Database Integration:* Uses MySQL to store and retrieve data.  

## Installation

### Prerequisites
- *C++ Compiler* (e.g., g++)
- *MySQL Server*
- *MySQL Connector for C++*

### Steps
1. Clone the repository:  
   bash
   git clone https://github.com/your-username/car-rental-system.git
   cd car-rental-system
   
2. Install MySQL and configure the database using the provided SQL script.
3. Compile and run the project:  
   bash
   g++ car-rental-with-mysql.cpp -o car_rental -lmysqlcppconn
   ./car_rental
   

## Usage
- Run the program and follow the on-screen menu.
- Select options to book, return, or manage cars.
- View rental records and customer details.

## Contribution
Feel free to contribute! Fork the repo, make changes, and submit a pull request.

## License
This project is open-source and available under the *MIT License*.
