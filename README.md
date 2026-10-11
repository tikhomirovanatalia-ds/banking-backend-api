# Bank Application Backend (OOP System Design) 🏦

This repository contains the backend implementation for a new banking application developed using **Object-Oriented Programming (OOP)** in Python. The system handles core banking operations, manages multiple card types, processes financial transactions, and implements robust error handling.

### 📐 System Architecture & Core Classes

The business logic of the application is designed around **five interconnected classes**:

* **`Bank`** — The central authority. Responsible for issuing banking products (cards) and maintaining a global ledger of all system-wide transactions.
* **`Account`** — Stores critical financial account details, including the unique account number, active balance, and information about the account owner.
* **`Card`** — Manages operations directly tied to payment cards, handles sensitive card data, and executes financial actions.
* **`Transaction`** — A data class dedicated to storing structured records of each completed transaction.
* **`User`** — Holds specific user profile data, linked accounts, associated cards, and manages authentication details like the application PIN.

### ⚙️ Implemented Features & User Scenarios

The system was developed iteratively, covering the following key functionalities:
1. **Card Issuance:** Infrastructure for simulating bank product registration and card dispatching via the `Bank` class.
2. **Core Financial Transactions:** 
   * Checking card information and current balance.
   * Account replenishment (deposits).
   * Making purchases and processing payments.
   * Secure peer-to-peer (P2P) money transfers between different cards.
   * Tracking local transaction history.
3. **Product Diversification:** Support for different specialized card types tailored to various user preferences.
4. **Security & Profile Management:** Secure PIN management and modification flows.
5. **Robust Exception Handling:** Integrated customized error catching and exception layers to handle edge cases (e.g., insufficient funds, incorrect PINs, or missing accounts) to ensure system stability.

### 🛠️ Tech Stack & Concepts
* **Language:** Python 3
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Key Paradigms:** Object-Oriented Programming (Encapsulation, Inheritance, Polymorphism), Custom Exception Handling, Object Interaction Modeling.
