# Palm-Scanner-Payment-System
A Palm Scanner Payment System is a biometric payment solution where a person's palm vein pattern or palm print is linked to their bank account. Instead of using a card, cash, phone, or QR code, the user simply scans their hand to make a payment.

How the System Works
Step 1: User Registration
User creates an account in the system.
User provides:
Name
Phone number
Bank account details
Identity verification (CNIC, Passport, etc.)
The palm scanner captures the user's unique palm data.
The biometric template is encrypted and stored in a secure database.
Step 2: Bank Account Linking
The system connects the user's account with a bank account or digital wallet.
APIs from banks are used for secure transactions.
The user authorizes the system to perform payments.
Step 3: Payment Process
Customer selects products in a store.
Cashier enters the amount.
Customer places their palm over the scanner.
Scanner captures palm data.
System compares it with stored templates.
If matched:
User identity is verified.
Payment request is sent to the bank.
Bank approves the transaction.
Payment is completed instantly.
System Architecture
Palm Scanner
      |
      v
Biometric Recognition Module
      |
      v
User Database
      |
      v
Payment Gateway
      |
      v
Bank API
      |
      v
Transaction Result
Required Components
Hardware
Palm Vein Scanner
Computer or POS Terminal
Internet Connection
Receipt Printer (Optional)
Software
Frontend Application (React, Flutter, etc.)
Backend API (Django, Node.js, Spring Boot)
Database (MySQL, PostgreSQL)
Biometric Recognition Engine
Payment Gateway Integration
Database Design
Users Table
Field	Type
UserID	INT
Name	VARCHAR
Phone	VARCHAR
BankAccount	VARCHAR
PalmTemplate	BLOB
Transactions Table
Field	Type
TransactionID	INT
UserID	INT
Amount	DECIMAL
DateTime	DATETIME
Status	VARCHAR
Security Features
Biometric data encryption
HTTPS communication
Two-factor authentication for registration
Anti-spoofing detection
Secure bank APIs
Transaction logs






Advantages
 No need for cards or cash
 Fast payments (2–3 seconds)
 Difficult to steal biometric data
 Convenient user experience
 Contactless payment





Challenges
 Privacy concerns
 Expensive hardware
 Integration with banks
 Compliance with financial regulations
 False acceptance/rejection rates

Real-World Examples

Some companies already use similar technology:

Amazon – Amazon One uses palm recognition for payments and identification.
Tencent – Has tested palm-payment systems in China.
Alipay – Uses palm recognition for payments in some locations.
Technologies You Can Use

If you want to build this as a university Final Year Project:

Frontend: React.js or Flutter
Backend: Django REST Framework
Database: PostgreSQL
AI/ML: OpenCV + TensorFlow
Authentication: JWT
Payment Integration: Bank APIs or sandbox payment gateways
Cloud: AWS or Azure
FYP Scope

Project Title:
"Biometric Palm-Based Secure Payment System"

Main Modules:

User Registration
Palm Enrollment
Palm Recognition
Bank Account Linking
Payment Processing
Transaction History
Admin Dashboard
Fraud Detection

This is a strong Final Year Project because it combines Cyber Security, Artificial Intelligence, Biometrics, Database Systems, and FinTech in one system.
