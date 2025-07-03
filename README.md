
# 💳 Bank Management System (Python CLI Project)

This is a simple **command-line-based Bank Management System** built using **Python**. It allows users to perform basic banking operations like creating an account, viewing details, depositing, and withdrawing money. All data is stored locally in a `.txt` file.

## 🧾 Features

- Open a new account
- View account details
- Deposit money
- Withdraw money
- Account number auto-generation
- File-based data persistence

## 📁 File Structure

- `bank_system.py`: Main Python script containing the complete logic.
- `account.txt`: Stores account information in list format (auto-created during runtime).

## ⚙️ How to Run

1. Make sure you have Python installed (version 3.6+).
2. Clone this repository or download the file.

```bash
git clone https://github.com/yourusername/bank-system.git
cd bank-system
```

3. Run the Python script:

```bash
python bank_system.py
```

> Note: You may need to update the file path in the script to store/read from `account.txt` correctly.

## 📌 Example Flow

```text
--------BANK SYSTEM--------
Open New Account press 1 :
View Account Detail press 2 :
Deposit money press 3 :
Withdraw Money press 4 :
Enter your choice (1 to 4) :
```

## 🛠 Technologies Used

- Python (Standard Library)
- File handling (`open`, `read`, `write`)

## 📒 Limitations

- No GUI (Command-line only)
- No password encryption
- File path is hard-coded
- No data validation for phone numbers or PIN security

## 🚀 Future Improvements

- Add user authentication
- Switch to database (like SQLite)
- Add transaction history tracking
- Improve error handling and input validation

## 👨‍💻 Author

- **Ishant Bansal**  
Feel free to connect or suggest improvements.


