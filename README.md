# Basic-bank-system
This project is a simple Java-based banking system that demonstrates the fundamentals of object-oriented programming.
It includes three main components: a Bank class that manages all accounts, an Account class that stores individual customer information, and a BankingSystem main class that runs the program. 
The system uses a HashMap to store accounts by their account numbers, allowing quick access and easy management of customer data. Each account contains a customer’s name, account number, and current balance.
The program allows you to create new accounts, deposit money into existing accounts, and display detailed account information.
When a transaction is made, the system checks whether the account exists and then updates the balance accordingly. 
If an account number is not found, the system displays an appropriate error message. This setup helps demonstrate how real banking operations might be simulated through basic data structures.
In the sample code, two accounts are added—one for John Doe and another for Jane Smith. 
The program then performs a transaction on John’s account and attempts to access a non-existing account, showing how the program handles invalid input. Finally, it displays the complete details of both existing accounts. This project is great for beginners who want to learn how to build simple systems using Java classes, methods, collections, and clean logical flow.
You can compile the program using javac BankingSystem.java and run it with java BankingSystem. This basic structure can be expanded further by adding features such as withdrawals, transaction history, user input via a menu, or persistent storage using files or databases.
