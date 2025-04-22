# 🛠️ Windows Optimization Script

This Python script runs a PowerShell command to download and execute [Chris Titus Tech's Windows Utility](https://christitus.com/win), which provides a GUI for optimizing and debloating Windows.

> ⚠️ **Warning**: This script executes a remote PowerShell script with elevated system access. Always review the code you download and run from the internet.

---

## 📦 Features

- One-liner setup for Chris Titus' Windows Utility
- Automates PowerShell execution via Python
- Ideal for custom Windows provisioning scripts or IT automation

---

## 🚀 How to Use

### 🐍 Requirements

- Python 3.x
- Windows OS

### 🔧 Installation & Execution

1. Clone the repository or copy the script.
2. Run the script using Python:

```bash
py main.py
```

> Make sure you're running the terminal with **Administrator privileges**, as the script makes system-level changes.

---

## 🧠 What It Does

The script runs the following PowerShell command:

```powershell
irm "https://christitus.com/win" | iex
```

Which downloads and executes the Chris Titus Windows Utility. This tool provides a graphical interface to:

- Debloat Windows
- Tweak performance settings
- Configure privacy options
- Manage Windows features and services

---

## 🔒 Disclaimer

Use at your own risk. The author of this repo is not responsible for any damage or unintended effects caused by running this script. Always read and understand what a script does before running it, especially with elevated permissions.

---

## 🙌 Credits

- [Chris Titus Tech](https://christitus.com/) — Original creator of the Windows Utility
