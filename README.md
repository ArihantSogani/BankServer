Bank Management System

📋 Overview
A comprehensive Python-based command-line banking application that simulates core banking operations. This system enables users to manage customer accounts, process financial transactions, and maintain persistent account records through file storage.

Account Management

Create Accounts - Open new savings or current accounts with initial deposits

Close Accounts - Remove accounts from the system

Modify Accounts - Update account holder information and balances

Transaction Processing

Deposits - Add funds to existing accounts
Withdrawals - Remove funds with proper balance verification
Balance Inquiry - Check current account balances

System Tools

Account Listing - View all registered accounts and their details
Data Persistence - Account information is maintained between sessions

🔧 Requirements

Python 3.x
Standard libraries:

pickle (for data persistence)
os (file operations)
pathlib (file path handling)

📥 Installation

# Clone the repository
git clone https://github.com/username/bank-management-system.git

# Navigate to the project directory
cd bank-management-system

# Run the application
python bank_management.py

🖥️ Usage
Upon launching the application, you'll be presented with the main menu:

MAIN MENU
        1. NEW ACCOUNT
        2. DEPOSIT AMOUNT
        3. WITHDRAW AMOUNT
        4. BALANCE ENQUIRY
        5. ALL ACCOUNT HOLDER LIST
        6. CLOSE AN ACCOUNT
        7. MODIFY AN ACCOUNT
        8. EXIT
        Select Your Option (1-8)

💰 Account Types

Savings (S) Minimum Initial Deposit : 500
Current (C) Minimum Initial Deposit : 1000

🗄️ Data Storage
The system stores all account information in accounts.data using Python's pickle module, ensuring data persists between program executions.
🚀 Future Enhancements

Enhanced security with user authentication

Transaction history and statement generation

Interest calculations for savings accounts

Email notifications for transactions

Graphical user interface (GUI)



