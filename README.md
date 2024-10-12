# Python Project

## Description

This repository contains various Python scripts and projects developed by Marcello Ardika Raharja. Each script demonstrates different aspects of Python programming, including data manipulation, algorithm implementation, and more. The code is well-commented to assist in understanding and further development.

## Project List
## Project 1: Food-Go Mobile App

### Overview
The **Food-Go Mobile App** is a simple command-line application written in Python that simulates an interactive food ordering experience. Users are prompted to enter their name and select a meal from a predefined menu. The app calculates the total cost of the order, applying promotional discounts, tax, and additional discounts based on the total amount.

### Features
- **Menu Selection:** Users can choose from a list of food items such as Bakso, Mie Ayam, Kepiting, and Spaghetti.
- **Dynamic Pricing:** The app calculates the price based on the selected food item.
- **Promotional Discounts:** Users can enter a promo code to receive a discount on their order.
- **Additional Discounts:** The app applies tiered discounts based on the total amount of the order.
- **Tax Calculation:** A 10% tax is automatically added to the final price.
- **Final Receipt:** The app provides the user with the final total after all calculations.

### Code Functionality
1. **Menu Display:** Shows the available food options.
2. **User Input:** Collects the user's choice and applies the corresponding price.
3. **Promo Code:** If a valid promo code is entered, a 25% discount is applied.
4. **Tiered Discounts:** Further discounts are applied depending on the total order amount.
5. **Tax Addition:** Adds a 10% tax to the final order price.
6. **Receipt:** Displays the final price and thanks the user for their order.

---

## Project 2: Online Banking System

### Overview
The **Online Banking System** is a Python-based command-line application designed to simulate a basic online banking experience. The app allows users to create an account, deposit funds, withdraw money, transfer funds, and check their balance. It also handles user authentication through a PIN system and provides an interest rate calculation based on deposit amounts.

### Features
- **User Account Creation:** Users can create an account by setting a username and a 6-digit PIN.
- **Login System:** Secure login with username and PIN verification.
- **Forgot PIN Functionality:** Users can reset their PIN if they forget it.
- **Deposit Funds:** Users can deposit money into their account.
- **Withdraw Funds:** Users can withdraw money, with checks to ensure sufficient balance.
- **Transfer Funds:** Users can transfer money to another account by entering an 8-digit account number.
- **Check Balance:** Users can view their current account balance at any time.
- **Interest Rate Calculation:** The system calculates and displays the interest rate based on the deposited amount.

### Code Functionality
1. **Account Management:**
   - **Sign In:** Allows new users to create an account with a username and 6-digit PIN.
   - **Login:** Existing users can log in using their username and PIN.
2. **Banking Operations:**
   - **Deposit:** Users can deposit funds, which will be added to their account balance.
   - **Withdraw:** Users can withdraw funds if the balance is sufficient.
   - **Transfer:** Allows users to transfer funds to another account if the account number is valid and funds are available.
   - **Check Balance:** Displays the current balance of the user's account.
   - **Interest Rate:** Calculates the interest rate based on the deposited amount.
3. **Error Handling:**
   - **PIN Validation:** Ensures the PIN is exactly 6 digits.
   - **Account Number Validation:** Ensures the account number for transfers is 8 digits.
   - **Balance Checks:** Ensures sufficient funds are available before withdrawals or transfers.
4. **User Experience:**
   - **Prompt Messages:** Guides users through different operations with clear instructions.
   - **Looping for Multiple Transactions:** Allows users to perform multiple transactions in a single session.

## Requirements

- Python 3.x
- Any necessary Python libraries can be installed using `pip install -r requirements.txt` if a `requirements.txt` file is provided.

**Note:** Copying, forking, and cloning these repositories (PYTHON) are strictly forbidden and not allowed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact:

- **Maintainer Name:** [Marcello Ardika Raharja]
- **Email:** [ardikamarcel@gmail.com]

Thank you for visiting the Python Project repository!
