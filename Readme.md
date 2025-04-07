# Bank Fund Management System using OOP and File Handling

This is a **Bank Fund Management System** implemented in Python. It uses **Object-Oriented Programming**, **Multilevel Inheritance**, and **file handling** to simulate real-world bank operations.

---

## 📌 Features
- Multiple Banks and Branches
- Account Creation with Random Account Numbers
- Deposit & Withdrawal Functionality
- Account Closure
- Fund and Account Count Updates Across All Bank Levels
- Permanent Data Storage using `.txt` Files

---

## 🏦 Bank Structure
### Main Banks:
- RESERVE BANK
- STATE BANK
- TAMILNADU BANK

### Tamilnadu Bank Branches:
- CUDDALORE BRANCH
- TRICHY BRANCH
- CHENNAI BRANCH

---

## 🛠️ Functionalities
1. **Account Creation**
   - Generates a random 5-digit account number
   - Updates account and fund data in branch, parent bank, and reserve bank

2. **Deposit & Withdraw**
   - Transaction updates all relevant bank levels

3. **Close Account**
   - Refunds the fund and updates the account/fund data across all levels

4. **Data Storage**
   - Uses file handling to store data in `.txt` file permanently
   - Reads existing data on restart to resume operations

---

## 💻 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/bank-management-system.git
   ```
2. Navigate to the folder:
   ```bash
   cd bank-management-system
   ```
3. Run the Python file:
   ```bash
   python Bank.py
   ```

---

## 🗂 Sample Data File Format (demo.txt)
```
4250
11
4500
16
5000
26
```

---

## 📎 Technologies Used
- Python 3
- Object-Oriented Programming (OOP)
- Multilevel Inheritance
- File Handling (`.txt`)

---

## 📬 Contact
For any queries, reach out to:
**[Aakash M]** – [aakash13022002m@gmail.com] – [Aakash M| Linkedin]

---

## 📄 License
This project is open-source and free to use under the [MIT License](LICENSE).
