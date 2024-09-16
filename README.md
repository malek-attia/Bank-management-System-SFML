# GUI Bank Management System

This project is a comprehensive **Bank Management System** built with **C++** and **SFML**, designed to simulate real-world banking operations through a graphical user interface. The primary goal of this project is to offer an intuitive and interactive banking experience, while demonstrating advanced programming techniques in C++.

## Key Features

### 1. **Account Management**
   - **Create Accounts**: Users can create new bank accounts with unique account numbers, names, and initial deposits.
   - **Edit/Delete Accounts**: Provides options to update account details or close an account.
   - **Data Persistence**: All account data is stored in a local file/database to ensure consistency and ease of access.

### 2. **Transaction Management**
   - **Deposit, Withdraw, Transfer**: The system supports common banking transactions, allowing users to perform deposits, withdrawals, and transfers between accounts.
   - **Transaction History**: Each account keeps a detailed record of all transactions for reference.
   - **Transaction Validation**: All transactions are validated to ensure account balance sufficiency and other business rules, preventing invalid operations (e.g., overdrafts).

### 3. **Searching and Sorting**
   - **Efficient Search Algorithms**: Users can search for accounts by account number, name, or other criteria, leveraging efficient search techniques to reduce lookup times.
   - **Sorting Techniques**: The project implements **Merge Sort** to order accounts by balance, name, or account number, ensuring quick access to sorted account data.

### 4. **Validation Mechanisms**
   - **Input Validation**: The system ensures that user input is correctly formatted and within acceptable ranges (e.g., preventing negative deposits or invalid account numbers).
   - **Error Handling**: Comprehensive error handling is integrated throughout the project to manage invalid inputs and system-level errors gracefully, improving overall user experience.

### 5. **Graphical User Interface (GUI)**
   - Built with **SFML**, the project offers a user-friendly GUI that includes buttons, forms, and data tables to interact with the system's features. 
   - The graphical interface provides a seamless way to manage accounts, track transactions, and navigate the system with ease.

### 6. **Advanced Data Structures**
   - **Linked Lists & Dynamic Arrays**: The project employs dynamic data structures to manage account data efficiently, enabling real-time updates and optimal memory usage.
   - **Efficient Sorting**: With **Merge Sort**, the system ensures that account data is sorted in optimal time complexity (O(n log n)), allowing for scalable performance as the number of accounts grows.

### 7. **Transaction Tracking**
   - **Deposit/Withdraw Management**: Each account supports deposits and withdrawals, with real-time balance updates and error prevention for insufficient funds.
   - **Transfer Between Accounts**: Users can seamlessly transfer money between accounts, with built-in checks to ensure the integrity of transactions.
   - **Transaction Logs**: All account-related transactions are logged, allowing users to view a complete history of actions taken on each account (e.g., transfers, deposits, withdrawals).

## Development Effort

This project demonstrates the application of **Object-Oriented Programming (OOP)** principles such as encapsulation, inheritance, and polymorphism to build a modular and maintainable codebase. Each major feature is encapsulated in separate classes that interact with each other through well-defined interfaces.

Key areas of focus include:
- **Modular Design**: The project is divided into classes for accounts, transactions, and the graphical interface, making the system easy to maintain and extend.
- **Algorithm Implementation**: Efficient algorithms such as **Merge Sort** and search techniques were implemented from scratch to optimize performance for large datasets.
- **File Handling**: Data persistence is achieved through file handling, allowing the system to save and load account details, transactions, and configurations between sessions.

## Conclusion

This GUI Bank Management System showcases not only core banking features like account management and transaction tracking, but also demonstrates advanced C++ programming skills, including efficient sorting algorithms, input validation, and the use of modern graphical libraries like **SFML**. This project represents a culmination of significant effort to integrate multiple complex concepts into a fully functional banking application.

## Demo

[(demo)[demo/demo.mp4]](https://github.com/user-attachments/assets/b66c084f-4930-4a40-8554-363719a9954b)
