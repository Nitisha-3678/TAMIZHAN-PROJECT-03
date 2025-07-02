# 🔑 Keylogger Implementation (Educational Use Only)

This project demonstrates a simple **keylogger** implemented in Python using the `pynput` library. It captures and logs keystrokes to a timestamped `.txt` file for educational and ethical purposes only.

## ⚠️ DISCLAIMER

> ❗ This tool is created **strictly for educational purposes**.  
> ❗ Do **NOT** use this script on any device without **explicit permission**.  
> ❗ Unauthorized usage is illegal and unethical.

---

## 🧠 Features

- Captures all keystrokes (including special keys)
- Logs keystrokes into a text file with timestamps
- Automatically creates a `keylogs/` directory if it doesn’t exist
- Lightweight and runs silently in the background

---

## 🛠️ Requirements

- Python 3.x
- `pynput` module

Install the required module:
pip install pynput
📂 Project Structure
keylogger-implementation/
├── keylogger.py
└── keylogs/
    └── log_YYYY-MM-DD_HH-MM-SS.txt  # Sample log file
🚀 Run the script:
python keylogger.py
Keystrokes will be saved in the keylogs/ folder with a timestamped filename.

📝 Example Log Output
[2025-07-02 11:45:23] Key pressed: a
[2025-07-02 11:45:24] Key pressed: b
[2025-07-02 11:45:25] Key pressed: Key.space
[2025-07-02 11:45:26] Key pressed: c
📌 Educational Use Cases
Understand how keylogging works internally
Learn about ethical hacking and monitoring tools
Demonstrate the importance of endpoint protection

❌ Responsible Usage
Please ensure that you use this code only in ethical, legal, and approved environments such as:
Lab environments
Your own personal system
With proper authorization for demonstration or testing
