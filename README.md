# GSMPNSNG Installer

GSMPNSNG Installer is a simple shell script project designed to help users install required packages easily on **Arch Linux** and Arch-based distributions.

This repository was created as a learning project to demonstrate the use of **Git**, **GitHub**, and **shell scripting**, especially for beginners.

---

## 📌 Features
- Simple and easy-to-use installation script
- Written in Bash (`.sh`)
- Can be executed directly from the terminal
- Suitable for learning Git and GitHub workflow

---

## 🛠 Tools Used
- **Neovim** – text editor used to write and edit the script
- **Terminal (Konsole)** – used to run Git and shell commands

---

## 📦 Dependencies
The following packages are used in this project:
- `git` – version control system
- `neovim` – text editor
- `base-devel` – common development dependencies on Arch Linux
- `less` – pager used by Git to display output

---

## 📥 Installation

### 1. Clone the repository
bash
'''git clone https://github.com/letmeburn/gsmpnsng-installer.git'''

2. Enter the project directory

'''cd gsmpnsng-installer'''

3. Give execute permission to the script

'''chmod +x install.sh'''

4. Run the installer

'''./install.sh'''

📄 install.sh Overview

The install.sh script is a Bash script that installs required packages using pacman.

Example:

#!/bin/bash

echo "Starting GSMPNSNG installation..."
sudo pacman -Sy --noconfirm git neovim
echo "Installation completed."

🚀 Git Workflow Used

This project demonstrates a basic Git workflow:

    Initialize Git repository (git init)

    Add files to staging area (git add)

    Commit changes (git commit)

    Push to GitHub using a Personal Access Token (PAT)

🔐 Authentication Note

GitHub no longer supports password authentication for Git operations.
All push operations are done using a Personal Access Token (PAT) instead of an account password.
🎯 Purpose of This Project

    Learning Git and GitHub basics

    Practicing shell scripting on Arch Linux

    Creating a simple installer script

    Sharing projects publicly via GitHub

📜 License

This project is open-source and free to use for learning purposes.
👤 Author

Arshavin
