﻿# Password-manager

## Introduction

This Password Manager is a simple Python program that allows you to store and manage your passwords. It uses encryption provided by the `cryptography` module to ensure that passwords are protected and cannot be accessed without a master password.

 ⚠️ **Disclaimer:** This program is intended as a learning exercise and a mini project. It is still in development and may not provide the level of security required for storing sensitive passwords. **Do not use it for storing important or critical passwords**. Always use reputable and well-audited password management tools for sensitive data.


## Features

- Securely store your passwords.
- Protect your passwords using strong encryption.
- Easily add, retrieve, and update stored passwords.

## Getting Started

1. **Prerequisites:**
   - Ensure you have Python 3.x installed on your system.

2. **Installation:**
   - Clone or download this repository to your local machine.

3. **Dependencies:**
   - Install the required dependencies by running:
     ```
     pip install cryptography
     ```

4. **Usage:**
   - Run the `password_manager.py` script:
     ```
     python password_manager.py
     ```

5. **Master Password:**
   - You will be prompted to set a master password during the first run. Make sure it's strong and memorable, as it will be required to access your stored passwords.

6. **Managing Passwords:**
   - Use the prompt options to add, retrieve, or update passwords.

## Troubleshooting

- If you forget your master password, there is no way to recover your stored passwords.


## Acknowledgments

- This program relies on the `cryptography` module for encryption. Learn more about it [here](https://cryptography.io/en/latest/).

