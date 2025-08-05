🏦 Bank Management System
This repository contains a simple bank management system developed in Python. It's available in two versions: a Command-Line Interface (CLI) application and a Streamlit Web Application. Both versions provide core banking functionalities and use a JSON file for persistent data storage.

🌟 Features
Create Account: Open a new bank account with user details. The system validates that the user is over 18 and the PIN is exactly 4 digits.

Persistent Data: All account information is saved to a data.json file, so your data remains even after you close the application.

Deposit: Add funds to an account with a deposit limit of $10,000.

Withdraw: Remove funds from an account, with a check for an insufficient balance.

Show Details: View all details for a specific account.

Update Info: Modify a user's name, email, or PIN.

Delete Account: Permanently remove an account after a user confirmation.

💻 Technologies Used
Python: The core programming language.

JSON File: Used for simple, persistent data storage.

Streamlit (Web App Version): A powerful library for creating interactive web applications with pure Python.

Command-Line Interface (CLI Version): The application is text-based and run through a terminal or command prompt.

🚀 Getting Started
To run either version of the application, follow the instructions below.

Prerequisites
You must have Python installed on your system.

Option 1: Command-Line Interface (CLI) Version
Save the Code: Copy the CLI code into a file named cli_bank_app.py.

Run the Application: Open your terminal, navigate to the directory where you saved the file, and run:

python cli_bank_app.py

Option 2: Streamlit Web App Version
Install Streamlit: This version requires the streamlit library. Install it by running:

pip install streamlit

Save the Code: Copy the Streamlit code into a file named bank_app.py.

Run the Application: In your terminal, navigate to the directory where you saved the file and run:

streamlit run bank_app.py

A new browser tab will open automatically with the web application running.

📄 Code
The complete code for both the CLI and Streamlit versions is available in the repository.

[Code for CLI Version]

[Code for Streamlit Version]
