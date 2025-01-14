# Personal Finance Manager

A simple Java-based Personal Finance Manager that allows users to track their income and expenses, categorized by different types. The application saves transaction data in a text file and provides functionalities for adding, viewing, and managing transactions.

## Features

- **Add Transaction**: Allows the user to add a new transaction with description, amount, type (Income/Expense), and category (Salary, Food, Entertainment, etc.).
- **View Transactions**: Displays a list of all transactions along with total income, total expenses, and the net balance.
- **Transaction Persistence**: Transactions are saved in a file (`transactions.txt`) to retain data across app restarts.
- **Expense Validation**: Ensures that the total expenses do not exceed the total income.
  
## Requirements

- Java Development Kit (JDK) 8 or above
- A Java IDE (e.g., VS Code, IntelliJ IDEA, Eclipse, NetBeans) or terminal/command line for compiling and running the application

## Setup Instructions

1. Clone this repository or download the project files.

   ```bash
   git clone https://github.com/your-username/FinanceManager.git

2. Open the project in your preferred IDE or text editor.

3. Make sure the transactions.txt file exists in the project directory (the app will create this file automatically if it's not found).

4. Run the FinanceManager.java class to start the application.
   ```bash
   javac FinanceManager.java Transaction.java
   java FinanceManager
5. The GUI will open, and you can begin adding transactions and viewing your financial data.

## File Structure
- FinanceManager.java: Main class for the application, which contains the GUI logic and handles transactions.
- Transaction.java: Defines the Transaction class with properties like description, amount, type, and category.
- transactions.txt: File where transactions are stored persistently.

## Developed By
Nageshwar Bedge
