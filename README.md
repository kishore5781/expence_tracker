# Personal Expense Tracker

The Personal Expense Tracker is a Python-based console application that runs in a loop until exited, helping users manage their monthly budget by logging and analyzing expenses. Data is stored in expense.csv for persistent tracking.

## Features





### Add Expense
Users input a date (YYYY-MM-DD), category (e.g., Food, Transport), and amount. Entries are appended to expense.csv (write operation).



### View Expenses
Reads expense.csv and displays a formatted table of all expenses, showing Date, Amount, and Category (read operation).



### Track Budget
Takes a monthly budget input, calculates total expenses from the CSV, and displays the spent and remaining amounts.



### Exit
Exits the loop with a friendly goodbye message.

## Benefits

This lightweight tool, requiring no external libraries, empowers users to plan and monitor finances effectively in standard Python.
