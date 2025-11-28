# Car Rental System

This application lets users manage car records and rent cars via a menu-driven console interface. Core operations include adding, updating, removing, listing, checking availability, and renting cars. Data is persisted in text files using C++ file streams.

--- 

## Table of Contents
- [About The Project](#about-the-project)
- [Key Features](#key-features)
- [Built With](#built-with)
- [Project Timeline & Team](#project-timeline--team)
- [Contribution & My Role](#contribution--my-role)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation & Usage](#installation--usage)
    
---

## About The Project

This project implements a console-based **Car Rental System** designed to manage car rental operations. Developed as part of the **Structured Programming** course curriculum at the **Faculty of Computer and Information Sciences, Ain Shams University**, the system provides functionalities for both customers and administrators to interact with car and user records.

It effectively demonstrates fundamental programming concepts such as data structuring, modular programming using functions, array management, and file handling in C++.

---

## Key Features

The system offers a comprehensive set of features for managing car rentals:

-   **User Authentication:** Secure login system for users based on their credentials.
-   **Car Management:**
    -   Add new cars to the system with details (brand, model, color, distance traveled).
    -   Update existing car details.
    -   Remove cars from the available records.
    -   View a list of all available cars.
    -   Check the availability status of a specific car.
-   **Customer Management:**
    -   Store customer details (name, mobile number, address).
    -   Facilitate car rental processes for registered customers.
-   **Data Persistence:** All customer and car data are stored and retrieved from the file system, ensuring data integrity across sessions.

---

## Built With

This project was developed using the following technologies and concepts:

-   **C++:** The primary programming language used.
-   **Structured Programming Principles:** Emphasizing functions, control structures, and data organization.
-   **Structs:** For defining custom data types for `Customer` and `Car` entities.
-   **Arrays:** Utilized for storing collections of customers and cars.
-   **File I/O:** For reading and writing persistent data to text files.

---

## Project Timeline & Team

This project was developed collaboratively as a coursework assignment for the **Structured Programming** module at the **Faculty of Computer and Information Sciences, Ain Shams University**.

* **Development Period:** March 6, 2024 – May 8, 2024.
* **Team Size:** Developed by a team of 6 students.
* *The project was structured and uploaded to GitHub for portfolio demonstration following the successful completion of the assignment.*

---

## Contribution & My Role

I was primarily responsible for designing and implementing the **Login System**, including:

- Designing the login flow and menu integration.

- Implementing credential validation and login checks.

- Reading and verifying user data from the file system (file formats, parsing, safe checks).

- Validating user input and handling basic login errors and retries.

- Integrating the login module with the rest of the system so the menu and car operations are accessible only to authenticated users.

This module served as the entry point for the application and ensured authorized access to car rental features.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need a C++ compiler installed on your system.
-   **GCC (GNU Compiler Collection):** Often included with development environments like MinGW on Windows, or readily available on Linux/macOS.
-   **An Integrated Development Environment (IDE):** Such as Visual Studio Code (with C++ extensions), Code::Blocks, or Dev-C++.

### Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AhmedYahiaEsmail/Car-Rental-System.git](https://github.com/AhmedYahiaEsmail/Car-Rental-System.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Car-Rental-System
    ```
3.  **Compile the source code:**
    If you are using GCC:
    ```bash
    g++ main.cpp -o car_rental_system
    ```
    *(Note: Replace `main.cpp` with the actual name of your main source file if it's different. If you have multiple `.cpp` files, list them all: `g++ file1.cpp file2.cpp -o car_rental_system`)*
4.  **Run the executable:**
    ```bash
    ./car_rental_system
    ```
    The system will launch in your console, prompting you for input to navigate through its features.

---
