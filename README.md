# Expense-Tracker
This is a Python program that helps the user to track their expenses. It uses an SQLite database to store information about expenses, such as the name, cost, and month when the expense was made. The program allows the user to add new expenses, view expenses made in the current month, and get statistics about all expenses.
Getting Started
To use this program, you need to have Python and SQLite installed on your computer. Once you have installed these dependencies, you can download the program and run it from the command line using the following command: python expense_tracker.py

##Features
Adding Expenses
The program allows the user to add new expenses by entering the name, cost, and month when the expense was made. The user will be prompted to enter these details when they choose the "Add Expense" option from the menu. The program will validate the input and add the expense to the database.

##Viewing Current Month Expenses
The program allows the user to view expenses made in the current month. When the user chooses the "View Current Month Expenses" option from the menu, the program will query the database and display a list of expenses made in the current month.

##Getting Statistics
The program allows the user to get statistics about their expenses. When the user chooses the "Get Statistics" option from the menu, the program will calculate and display the following information:

Average expense made this month
Total expenses made
Average expense made overall
Exiting the Program
The program allows the user to exit the program by choosing the "Exit" option from the menu. This will close the database connection and exit the program.

##Functions
The program contains three main functions:

make_db()
This function creates a new SQLite database if it does not already exist. It creates a table called "expense" with columns for the expense name, expense cost, and expense month.

getting_expense()
This function prompts the user to enter details about a new expense and adds it to the database. It validates the user input and handles any errors.

current_month_expense()
This function queries the database and displays a list of expenses made in the current month.

statistics()
This function calculates and displays statistics about all expenses stored in the database. It calculates the average expense made this month, total expenses made, and average expense made overall.

##Conclusion
This Expense Tracker program provides a simple and convenient way for users to track their expenses. With its user-friendly interface, users can easily add new expenses, view current month expenses, and get statistics about their overall expenses.
