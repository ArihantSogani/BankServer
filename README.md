Bank Management System
Overview
This Bank Management System is a Python-based application designed to simulate basic banking operations. It provides a command-line interface for managing customer accounts, handling transactions, and maintaining account records using file persistence.
Features

Create Account: Open new savings or current accounts with initial deposits
Deposit: Add funds to existing accounts
Withdraw: Remove funds from accounts (with balance checks)
Balance Enquiry: Check the current balance of any account
Account Listing: View all registered account holders and their details
Close Account: Remove an account from the system
Modify Account: Update account holder information and balance

Requirements

Python 3.x
Standard Python libraries (pickle, os, pathlib)

Installation

Clone or download this repository
Navigate to the project directory
Run the application:

python bank_management.py
Usage


The application presents a main menu with the following options:

NEW ACCOUNT - Create a new bank account
DEPOSIT AMOUNT - Add money to an existing account
WITHDRAW AMOUNT - Remove money from an existing account
BALANCE ENQUIRY - Check the balance of an account
ALL ACCOUNT HOLDER LIST - View all accounts in the system
CLOSE AN ACCOUNT - Delete an account from the system
MODIFY AN ACCOUNT - Update account details
EXIT - Close the application

Data Storage
The system uses Python's pickle module to persist account data in a file named "accounts.data". This allows account information to be maintained between program sessions.
Account Types

Savings Account (S): Requires minimum initial deposit of 500
Current Account (C): Requires minimum initial deposit of 1000

Future Enhancements

Password protection for accounts
Transaction history logging
Interest calculation for savings accounts
GUI interface
