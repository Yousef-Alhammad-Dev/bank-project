# 🏦 Bank Management System

## 📌 Overview
Bank Management System is a **C++ console application** designed to manage clients and users in a small banking system.  
It uses **text files (Clients.txt & Users.txt)** for data storage and provides a flexible **permissions system** to control user access.

---

## ✨ Features

### 👤 Client Management
- Add new clients  
- Update client information  
- Delete clients  
- Display all clients  
- Search for clients by account number  

### 🧑‍💻 User Management
- Add new users  
- Update user information  
- Delete users (except Admin)  
- Display all users  
- Search for users by username  
- Flexible **permissions system** (full access or specific privileges)  

### 💰 Transactions
- Deposit money into accounts  
- Withdraw money (with balance validation)  
- Display all balances with total sum  

### 🔐 Authentication
- Login screen with username & password  
- Access control using permissions  
- Denied access message for unauthorized users  

---

## 🛠️ Technologies
- **C++** (core programming language)  
- **File I/O** for persistent storage  
- **Structs** for clients & users  
- **Enums** for menus & permissions  

---

## 🚀 How to Run

1. Compile the project using a C++ compiler (e.g., `g++ Project.cpp -o BankSystem`).  
2. Run the executable (e.g., `./BankSystem`).  
3. At the **login screen**, use the following credentials:  

   - **Username:** `Admin`  
   - **Password:** `1234`  

---

## 📂 File Structure
- `Project.cpp` → main source code  
- `Clients.txt` → stores client information  
- `Users.txt` → stores user information  

---

## 📜 License
This project is provided for learning and educational purposes. You are free to modify and use it, but it comes with **no warranty**.
