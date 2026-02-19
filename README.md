# Python-Compiler-Pro
An advanced GUI-based Python script compiler featuring PyArmor obfuscation, intelligent AST auto-splitting, and a built-in Inno Setup installer generator

# 🚀 Python Ultimate Compiler Pro V5.0

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![PyInstaller](https://img.shields.io/badge/PyInstaller-Supported-brightgreen)
![PyArmor](https://img.shields.io/badge/PyArmor-v8%2B_Integrated-orange)
![CustomTkinter](https://img.shields.io/badge/UI-CustomTkinter-blueviolet)
![License](https://img.shields.io/badge/License-MIT-green)

**Python Compiler Pro** is an advanced, all-in-one GUI tool designed to seamlessly obfuscate, compile, and package Python scripts into standalone Windows executables (`.exe`) and professional installers. 

It completely automates the hassle of using PyArmor and PyInstaller via terminal, and introduces an intelligent **AST Auto-Split Engine** to bypass script size limitations natively.

---

## ✨ Key Features

* **🛡️ One-Click Obfuscation & Compilation**: Automatically protects your code with PyArmor and compiles it into a `.exe` using PyInstaller in a single click.
* **🧠 Intelligent AST Auto-Split Engine**: Automatically detects if a script exceeds PyArmor's trial/AST node limits, intelligently splits the code at safe boundaries (classes/functions) to bypass the limit, compiles it, and restores the original script flawlessly.
* **🔍 Smart Module Detection**: Scans your entire project folder to automatically detect cross-script imports and applies `--hidden-import` and `--collect-all` to prevent "Module Not Found" errors.
* **📦 Built-in Inno Setup Generator**: Easily generate `.iss` scripts and compile professional Windows Installers directly from the GUI.
* **🛠️ Auto-Fix Engine**: Detects missing modules during compilation and automatically attempts to `pip install` them.
* **☁️ Cloud Command Fetcher**: Automatically updates backend CLI commands via cloud JSON configuration without needing a software update.
* **🧹 Smart Cleanup**: Automatically clears `__pycache__`, `build`, `dist`, and `.spec` files with one click.

🚀 How to Use
1. Compiling a Python Script
Run the tool: python main.py

Click 1. Select Script and choose your main .py file.

(Optional) Click 2. Select App Icon to add a custom .ico file.

(Optional) Click 3. Add Data/Files to include external assets (images, databases).

Choose between OneFile Bundle (single .exe) or OneDir Folder.

Check PyArmor v8+ Protection for code obfuscation.

Click 🚀 START BUILD. The tool will handle the rest!

2. Creating a Windows Installer
Switch to the 📦 Inno Setup Generator tab.

Select the compiled .exe file generated from the previous step.

Fill in the App Name, Publisher, and Website URL.

Add a custom setup icon and a Readme file (optional).

Click GENERATE & BUILD SETUP to instantly create a professional Windows installer.

⚠️ Disclaimer
This tool is intended for developers to protect and distribute their own intellectual property. Do not use this software for malicious purposes or to obfuscate malware.

👨‍💻 Developer
Developed with ❤️ by Kashif Khan.
If you found this tool helpful, please consider giving it a ⭐ on GitHub!

<img width="1366" height="768" alt="Screenshot (169)" src="https://github.com/user-attachments/assets/06ecccec-9b07-42df-83e0-bff28b4f6735" />

<img width="1366" height="768" alt="Screenshot (170)" src="https://github.com/user-attachments/assets/00a4676d-082b-4e6e-be65-9fece0d03d3e" />

<img width="1366" height="768" alt="Screenshot (171)" src="https://github.com/user-attachments/assets/b0ac09ee-2308-4f3a-ba39-b53bfeca9ea1" />


