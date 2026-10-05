# 🏦 Bank Management app

A simple banking web app built with **Python** and **Streamlit**. Users can create an account, deposit and withdraw money, view their details, update their information, and delete their account, all from a clean browser interface.

## Features

- **Create Account**: sign up with name, age, email and a 4-digit PIN
- **Deposit**: add money to an account
- **Withdraw**: take money out of an account
- **Show Details**: view the account information
- **Update Info**: change name, email or PIN
- **Delete Account**: permanently remove an account

Every action is verified with the account number and PIN.

## Tech Stack

- Python 3
- [Streamlit](https://streamlit.io/) for the user interface

## How to Use

1. Pick an action from the sidebar.
2. Fill in the form fields.
3. Click the action button to see a success or error message.

Start with **Create Account** and note your account number. You need it, along with your PIN, for every other action.

## Future Improvements

- Hash PINs instead of storing them in plain text
- Input validation for email and age
- Confirmation step before deleting an account
- Transaction history
- Move storage to a database such as SQLite

## Disclaimer

This is a learning project. It is **not** secure enough for real financial data.

**A Mokshit Rayudu**

- GitHub: [@mokshitrayudu](https://github.com/mokshitrayudu)
- LinkedIn: [linkedin.com/in/mokshitrayudu](https://linkedin.com/in/mokshitrayudu)
