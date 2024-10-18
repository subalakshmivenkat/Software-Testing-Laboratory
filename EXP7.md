# Ex.No: 7  ATM Applicationn
### DATE: 18-10-2024        
## NAME : SUBALAKSHMI V
### REGISTER NUMBER : 212222040162
### AIM: 
For ATM system study its system specifications and report various bugs

### Purpose:
The purpose of this exercise is to understand the functional and non-functional requirements of an ATM system and to identify any potential bugs or vulnerabilities that could affect the operation of the system. The ATM system allows users to perform transactions such as withdrawals, deposits, balance inquiries, and fund transfers.

### Scope:
The scope of this project is to explore and evaluate the key features of an ATM system, including its interaction with banking databases, the user interface, and its security protocols. The system's limitations, constraints, and possible bugs will also be investigated to improve the functionality and reliability of the ATM.

### Intended Audience:
This report is intended for:
- **Developers and testers** who are working on improving the reliability and security of ATM systems.
- **Banking institutions** looking to upgrade or implement new ATM systems.
- **System administrators and IT professionals** responsible for maintaining ATM infrastructure.

### Product Perspective:
The ATM system interacts with the bank's central server to provide real-time access to a user’s account information. It is an integral part of the banking infrastructure and acts as an intermediary between users and the bank's services. The system processes transactions based on user input (card insertion, PIN entry) and communicates with the back-end to perform transactions such as withdrawals and deposits.

### Product Functions:
Key functionalities of the ATM system include:
1. **Card Authentication**: Reads and authenticates the user's debit/credit card.
2. **PIN Verification**: Verifies the user's PIN for security.
3. **Withdrawal**: Allows users to withdraw a specified amount of money.
4. **Deposit**: Enables users to deposit cash or checks.
5. **Balance Inquiry**: Displays the user’s current balance.
6. **Fund Transfer**: Facilitates the transfer of funds between accounts.
7. **Transaction Receipts**: Prints or emails a transaction receipt.

### Operative Environments:
- **Hardware**: ATMs with card readers, PIN pads, cash dispensers, receipt printers, and a screen for user interaction.
- **Operating System**: Windows-based or Linux-based embedded systems for secure operations.
- **Network**: Secure, real-time network connectivity to the bank’s central servers.
- **Software**: Banking application software, including communication protocols for interacting with backend systems and payment networks (e.g., Visa, MasterCard).

### Design/Implementation Constraints:
- **Hardware limitations**: The ATM hardware may impose constraints on the speed of transactions, the amount of cash dispensed, or user interface responsiveness.
- **Security constraints**: The system must be designed with strong security measures (e.g., encryption, secure PIN entry) to prevent fraud.
- **Operational constraints**: Limited transaction types may be supported depending on the system's configuration and regional regulations.
- **User constraints**: Accessibility features (e.g., for visually impaired users) must be incorporated to meet diverse user needs.

### Assumptions and Dependencies:
- It is assumed that the ATM system will operate in a secure environment where transactions are protected by encryption and authentication measures.
- Dependencies include the bank’s central database, third-party payment processors (Visa, MasterCard), and reliable network connectivity.
  
### Software Interfaces:
- **User Interface**: Touchscreen or keypad-based interaction for users to input their selections.
- **Bank Database Interface**: Secure communication with the central banking database to update and retrieve account information.
- **Security Software**: Integration with security software to ensure encrypted data transmission and prevent fraud.

### Safety Requirements:
- The ATM must ensure the safety of users’ funds by preventing unauthorized access through the use of PIN verification, account locking after multiple failed attempts, and secure cash withdrawal processes.
- Emergency shutoff procedures must be implemented in case of technical failures or security breaches.

### Security Requirements:
- **PIN Encryption**: The user's PIN must be encrypted before transmission.
- **Card Data Protection**: The ATM should not store sensitive cardholder information.
- **Transaction Logs**: Detailed logs of all transactions should be kept securely for auditing.
- **Network Security**: The system should use secure communication channels (e.g., SSL/TLS) to prevent data interception.

### Possible Bugs:
1. **Card Reader Failures**: The card reader may fail to read the card or incorrectly detect invalid cards.
2. **PIN Input Errors**: The system may fail to validate correct PIN entries or lock out users prematurely.
3. **Network Issues**: The ATM may experience network disconnections leading to incomplete transactions or delays.
4. **Cash Dispenser Malfunctions**: The dispenser may deliver incorrect amounts or jam during operation.
5. **User Interface Glitches**: The screen may freeze or fail to display transaction options correctly.
6. **Session Timeout Bugs**: The ATM may unexpectedly log users out mid-transaction, leading to confusion or incomplete operations.

### Result:
Thus, the ATM system specifications were studied, and various bugs were reported based on the analysis. The output of the study was verified successfully, helping to identify areas for improvement in ATM reliability and security.
