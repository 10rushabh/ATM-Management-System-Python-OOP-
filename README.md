Project Summary: ATM Management System (Python OOP)

This project is a console-based ATM Management System developed using Python and Object-Oriented Programming (OOP) concepts.
It simulates basic ATM operations such as creating a PIN, depositing money, withdrawing money, and checking account balance.

The project focuses on:

Class & object usage

Encapsulation (PIN security)

Conditional logic

User interaction via command line
Project Direction / How the Project Works
1️⃣ Program Start

When the program starts, an object of the Atm class is created.

The constructor (__init__) initializes:

pin → empty string

balance → 0

The ATM menu is automatically displayed.

2️⃣ Menu Options

The user is prompted with the following options:

Option	Function
1	Create ATM PIN
2	Deposit money
3	Withdraw money
4	Check balance
5	Exit
3️⃣ Create PIN

User sets a PIN.

PIN is stored securely inside the object.

Required before deposit, withdrawal, or balance check.

4️⃣ Deposit Money

User enters PIN for verification.

If PIN is correct:

Amount is added to balance.

Else:

“Invalid PIN” message is shown.

5️⃣ Withdraw Money

PIN verification is required.

If balance is sufficient:

Amount is deducted.

If not:

“Insufficient funds” message is shown.

6️⃣ Check Balance

User enters PIN.

Current balance is displayed if PIN is correct.

7️⃣ Exit

Program terminates safely.
