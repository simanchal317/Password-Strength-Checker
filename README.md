🔐 Password Strength Checker (Python)

A simple and interactive Password Strength Checker built using Python.
It checks your password against multiple security conditions and gives feedback on how strong it is.
---

✅ Features
This tool evaluates password strength based on:

Minimum 8 characters

At least 1 digit

At least 1 uppercase letter

At least 1 lowercase letter

At least 1 special character


It gives output as Weak, Medium, or Strong.
---

🧠 How It Works

The script uses:

Python's any() function to check characters

Regular expressions (re module) to detect special symbols

A loop to allow continuous password checking until user types exit

---

📌 Usage

1. Run the Python script:

python password_checker.py


2. Enter your password when prompted.
3. Type exit anytime to quit.

---

📁 Code Overview

🔍 check_password_strength(password)

Checks the password against required conditions and returns the strength message.

💬 password_checker()

Handles user interaction and repeatedly checks passwords.


---

📝 Sample Output

Welcome to the Password Strength Checker!

Enter your password (or type 'exit' to quit): Hello123
Medium: Add special characters to make your password stronger.

Enter your password (or type 'exit' to quit): Hello@123
Strong: Your password is secure!
---

📦 Requirements

Python 3.x


No external libraries needed (only built-in re module).
