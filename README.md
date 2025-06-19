Caesar Cipher Tool
A simple Python program to encrypt and decrypt text using the Caesar Cipher algorithm — a classic substitution cipher used in cryptography for educational purposes.

🎯 Purpose
This tool allows users to:

Encrypt plain text using a shift value

Decrypt previously encrypted text

Learn how the Caesar Cipher algorithm works

Practice working with text manipulation and control flow in Python

✨ Features
Supports both encryption and decryption

Interactive console interface

Handles uppercase and lowercase letters correctly

Keeps non-alphabetic characters unchanged (spaces, punctuation, etc.)

Allows user-defined shift value (1-25)

Input validation and error handling

Option to perform multiple operations in one run

Includes a demo function with example outputs

🛠️ How It Works
The Caesar Cipher shifts each letter in the text by a given number of positions:

Example with shift 3:
A → D, B → E, C → F, ..., X → A, Y → B, Z → C

The same shift (but reversed) is used to decrypt.

Non-letter characters (punctuation, spaces) remain unchanged.

🚀 Getting Started
Prerequisites
Python 3.x installed on your machine

Running the Program
Download the script: caesar_cipher.py

Run in terminal or command prompt:

bash
Copy
Edit
python caesar_cipher.py
Follow on-screen instructions:

Enter the text

Choose shift value (1-25)

Select operation: Encrypt or Decrypt

See the result displayed!

Example
text
Copy
Edit
=== Caesar Cipher Tool ===
Enter the text: Hello World
Enter shift value (1-25): 3
Choose operation:
1. Encrypt
2. Decrypt
Enter choice (1 or 2): 1

=== Encryption Result ===
Original text: Hello World
Shift value: 3
Result: Khoor Zruog
📖 Educational Value
Learning Objectives
Understand Caesar Cipher encryption and decryption

Practice input handling and validation in Python

Work with string manipulation and ASCII values

Explore interactive command-line programming

Use Cases
Cryptography lessons

Python learning projects

Educational tools and exercises

Classic algorithm demonstrations

📋 Limitations
Only works with alphabetic characters (A-Z, a-z)

No support for Unicode or emojis

Simple static shift — not secure for real-world encryption

🔧 Customization
You can easily modify:

Shift value range

Support for larger alphabets

Case sensitivity options

Add support for user-defined alphabets

Add file input/output support

🤝 Contributing
Suggestions and contributions are welcome:

Improve algorithm flexibility

Add GUI version (Tkinter / PyQt / Web)

Add support for variable shift patterns

Internationalization

📄 License
This project is licensed under the MIT License.

⚠️ Legal Disclaimer
This tool is for educational purposes only.
The Caesar Cipher is not secure for protecting sensitive data — use modern encryption algorithms for real-world security.
