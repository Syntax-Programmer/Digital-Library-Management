# Digital Library Management

Welcome to Digital Library Management!
This project implements

## Running the Project

- Clone the project from github

    ```bash
    git clone https://github.com/Syntax-Programmer/Digital-Library-Management.git
    ```

- Get requirements

    ```bash
    pip install -r requirements.txt
    ```

- Make sure you have mysql cli server installed on your local pc

- Edit the sqlinfo.txt with your localhost SQL uname and passwd

    ```json
    {
    "uname": "username",
    "passwd": "password"
    }
    ```

- Test data case is given in SQL.txt file. Use it to simulate a testing environment

- Run the code

    ```bash
    python Main.py
    ```

- Enjoy

## Overview

The Library Management System (Digital Library) project is designed to streamline user enrollment and book management within a digital library environment. This software allows users to search for news and Wikipedia articles, as well as provides authentication for both administrators and users to securely access their respective panels. Users can view available books and track the details of the books they have borrowed.

The system supports login access via user ID and password, enabling both admins and regular users to interact with the platform. Admins have exclusive permissions to add, delete, and update user and book data in the database, ensuring data integrity and secure management. Information retrieval is swift and efficient, and the interface is highly user- friendly, enhancing accessibility.

The Digital Library project aims to modernize library management by developing a system that is intuitive, fast, and cost-effective. Additionally, the system includes a notes feature, allowing users to add personal notes to the database at any time. This enhances the flexibility and usability of the platform, making it a valuable tool for both administrative and personal use.
