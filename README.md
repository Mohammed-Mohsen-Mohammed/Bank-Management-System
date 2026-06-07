# 🏦 Bank Management System

A console-based Bank Management System developed in C++ that allows managing bank clients and performing banking transactions.

This project was implemented in two phases:

### Phase 1 - Client Management System
Basic CRUD operations for bank clients:
- Add new clients
- View all clients
- Update client information
- Delete clients
- Search for clients

### Phase 2 - Transactions Extension
Extended the system by adding banking transaction features:
- Deposit money
- Withdraw money
- View all client balances
- Calculate total balances across all accounts

---

## 🚀 Features

### Client Management
- Create new client accounts
- Prevent duplicate account numbers
- Search clients by account number
- Update client information
- Delete existing clients
- Display all clients in a formatted table

### Transactions
- Deposit funds into client accounts
- Withdraw funds with balance validation
- Prevent overdrawing accounts
- Display balances of all clients
- Show total bank balances

### Data Persistence
- Client data is stored in a text file (`Clients.txt`)
- Data is automatically loaded when the program starts
- Changes are saved immediately after operations

---

## 🛠️ Technologies Used

- C++
- File Handling (fstream)
- STL Vector
- Structured Programming
- Console Application Development

---

## 📂 Project Structure

```
BankManagementSystem/
│
├── Clients.txt        # Database file
├── main.cpp           # Application source code
└── README.md
```

---

## 📋 Main Menu

```
[1] Show Client List
[2] Add New Client
[3] Delete Client
[4] Update Client Info
[5] Find Client
[6] Transactions
[7] Exit
```

### Transactions Menu

```
[1] Deposit
[2] Withdraw
[3] Total Balances
[4] Main Menu
```

---

## 🔒 Validation Features

- Duplicate account number prevention
- Input validation for menu selections
- Deposit amount validation
- Withdrawal balance checking
- Invalid input handling

---

## 📸 Sample Operations

### Add Client
- Enter account number
- Enter PIN code
- Enter client name
- Enter phone number
- Enter initial balance

### Deposit
- Select account
- Enter deposit amount
- Confirm transaction
- Balance updated automatically

### Withdraw
- Select account
- Enter withdrawal amount
- System validates available balance
- Transaction executed after confirmation

---

## 🎯 Learning Objectives

This project was built to practice:

- File handling in C++
- Structs and vectors
- Data persistence
- Menu-driven applications
- Input validation
- Software extension and maintenance
- Banking transaction processing

---

## 👨‍💻 Author

Mohamed Mohsen

Computer Science & Artificial Intelligence Graduate
