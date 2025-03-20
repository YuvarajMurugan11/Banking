
# MiniProject - Simple Bank Management System

## Overview
This project is a simple **Bank Management System** implemented in Java. It allows users to create accounts, search for accounts, manage balances, and perform deposit and withdrawal transactions.

## Features
- Create a **Savings** or **Current** account.
- Search for an account by the account holder's name.
- Display the total number of accounts.
- List **VIP accounts** with balances above a user-defined threshold.
- Deposit and withdraw money from accounts.
- Check account balance.

## Project Structure
The project consists of the following classes:
- **`Account`** (Abstract Base Class)  
  - Defines common properties for all account types.
  - Implements `checkBalance()` method.

- **`SavingAccount`** (Derived Class)  
  - Implements `deposit()` and `withdraw()` methods for a savings account.

- **`CurrentAccount`** (Derived Class)  
  - Implements `deposit()` and `withdraw()` methods for a current account.

- **`Bank`**  
  - Manages a list of accounts.
  - Handles account creation, searching, and VIP account listing.

- **`MiniProject`** (Main Class)  
  - Provides a menu-based interface for user interaction.

## How to Run
1. Compile the Java file:  
   ```sh
   javac MiniProject.java
