PROJECT REPORT
ON
ATM MACHINE SIMULATION USING C++
Object-Oriented Programming (OOP) Project


Submitted by
Name: 
Register Number: AP25110010236
Department : CSE CORE
Year / Semester: 3rd semester, 2025-2029


Submitted to
Faculty Name: KUNAL BISWAS


Institution: SRM UNIVERSITY AP
Academic Year: 2026–2027

 CERTIFICATE
This is to certify that Akanksha Varma, Register Number AP25110010236, has completed the project titled “ATM Machine Simulation Using C++” under my guidance as part of the Object-Oriented Programming course.


Guide Signature: ____________________        Head of Department: ____________________

 ACKNOWLEDGEMENT
I would like to thank our faculty member and department for guiding me throughout this project. I am also grateful to my classmates and everyone who helped me understand the concepts and test the program. While working on this project, I got a chance to use C++ classes and objects and understand concepts such as encapsulation, abstraction, and input validation in a practical way.
ABSTRACT
This project is a simple ATM simulation developed using C++. It shows how common ATM services can work through a menu on the screen. First, the user enters a four-digit PIN. If the PIN is correct, the user can check the balance, deposit or withdraw money, view a mini statement, change the PIN, or exit the program. The project uses object-oriented programming. The BankAccount class manages the account details and transactions, while the ATM class displays the menu and interacts with the user. This is only a learning project, so it uses sample account details and is not connected to an actual bank.
TABLE OF CONTENTS
1.	1. Introduction
2.	2. Problem Statement
3.	3. Objectives
4.	4. Scope
5.	5. Software and Hardware Requirements
6.	6. OOP Concepts Used
7.	7. System Design and Working
8.	8. Algorithm
9.	9. Source Code
10.	10. Sample Test Cases
11.	11. Limitations and Future Enhancements
12.	12. Conclusion
13.	13. References
1. INTRODUCTION
An Automated Teller Machine, or ATM, helps people carry out basic banking tasks without going to a bank counter. In this project, I created a simple version of an ATM using C++. The program allows the user to enter a PIN and then choose services such as checking the balance, depositing money, withdrawing money, viewing recent transactions, and changing the PIN. It is a console-based project designed to help me understand how these operations can be programmed.
2. PROBLEM STATEMENT
The aim of this project is to create a menu-based C++ program that behaves like a basic ATM. The program should check the user's PIN before showing the available services. It should also stop users from withdrawing more money than they have, reject zero or negative transaction amounts, and display a clear message after each operation.
3. OBJECTIVES
