<h1 align="center">🖥️ Custom_Shell_Implementation_WIPRO</h1>

<p align="center">
  <b>A modular UNIX-like command shell written in C++</b>  
  <br>
  <img src="https://img.shields.io/badge/Language-C%2B%2B17-blue.svg">
  <img src="https://img.shields.io/badge/Platform-Linux%2FWSL-lightgrey.svg">
  <img src="https://img.shields.io/badge/Status-Working-brightgreen.svg">
  <img src="https://img.shields.io/badge/License-MIT-orange.svg">
</p>

---

## 📖 Overview
This project is a **Custom Command Shell** implemented in **C++17** as part of the Capstone/Assignment-2.  
It mimics the behavior of a basic Linux terminal and supports:
- Command parsing with quotes (`" "` and `' '`)
- Built-in commands like `cd`, `exit`, `jobs`, `fg`, `bg`
- External command execution (`ls`, `cat`, `grep`, etc.)
- Background processes using `&`
- Pipelining (`|`) and I/O redirection (`<`, `>`)
- Signal handling for `Ctrl + C` and `Ctrl + Z`
- Job tracking with status reporting

---

## 🧩 Features Breakdown

| Feature | Description | Example |
|----------|--------------|----------|
| 🧱 **Command Execution** | Run external Linux commands | `ls -l`, `cat file.txt` |
| 🛠️ **Built-ins** | Supports `cd`, `exit`, `jobs`, `fg`, `bg` | `cd /home`, `exit` |
| 🔀 **Pipes** | Connect multiple commands | `ls -l | grep txt` |
| 📁 **Redirection** | Input/Output redirection | `grep foo < input.txt > output.txt` |
| ⚙️ **Background Jobs** | Run jobs in background | `sleep 5 &` |
| ⏸️ **Signal Handling** | Handles `Ctrl + C` and `Ctrl + Z` | Interrupt / stop processes |
| 📋 **Job Control** | Resume/bring back jobs | `fg <pid>`, `bg <pid>` |

---

## ⚙️ Project Structure
