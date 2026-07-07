# 🚀 Ultimate Terminal & Git Cheat Sheet

Welcome to the command line! This guide will help you navigate your computer and track your code like a pro. 

---

## 📂 Part 1: The Terminal (Command Line)
The terminal is just a text-based way to move around your computer instead of clicking icons.

### 🧭 Moving Around (Navigation)
* **`pwd`** (Print Working Directory)
  * Shows exactly which folder you are currently standing in.
* **`ls`** (List)
  * Lists all files and folders inside your current folder.
* **`cd [folder_name]`** (Change Directory)
  * Moves you inside that folder (e.g., `cd Documents`).
* **`cd ..`** (Go Up)
  * Moves you backward out of the current folder into the parent folder.
* **`cd ~`** (Go Home)
  * Takes you instantly back to your main user home folder.

### 🛠️ Creating & Managing Files
* **`mkdir [folder_name]`** (Make Directory)
  * Creates a brand new, empty folder.
* **`touch [file_name]`** (Touch)
  * Creates a new empty file (e.g., `touch index.html` or `touch script.js`).
* **`rm [file_name]`** (Remove)
  * Deletes a file permanently. **Warning:** There is no Recycle Bin here!
* **`rm -r [folder_name]`** (Remove Recursive)
  * Deletes an entire folder and everything inside it.
* **`clear`** (Clear Screen)
  * Wipes the terminal screen clean so you have a fresh workspace.

---

## 🐙 Part 2: Git (Version Control)
Git is like a video game save system for your code. It tracks your changes so you can never accidentally ruin your project.

### 🎬 Starting a Project
* **`git init`** (Initialize)
  * Turns your current folder into a Git repository (starts tracking it).
* **`git status`** (Status)
  * Shows what files have been changed, added, or need to be saved.

### 💾 Saving Your Work
Saving in Git is a two-step process: **Staging** (packing the box) and **Committing** (taping it shut with a label).

* **`git add [file_name]`** (Add specific file)
  * Prepares a specific file to be saved.
* **`git add .`** (Add everything)
  * Prepares **all** changed files in the folder to be saved.
* **`git commit -m "your message here"`** (Commit)
  * Saves your staged changes permanently with a short description of what you did.

### 🌐 Connecting to GitHub (Remote)
* **`git clone [URL]`** (Clone)
  * Downloads an existing project from GitHub to your computer.
* **`git remote add origin [URL]`** (Add Remote)
  * Links your local computer project to a repository on GitHub.
* **`git push -u origin main`** (Push)
  * Sends your saved commits up to GitHub for the very first time.
* **`git push`** (Push subsequent times)
  * Sends your new saved commits to GitHub after the setup is done.
* **`git pull`** (Pull)
  * Downloads the newest changes made by others from GitHub to your computer.

---

## 💡 Quick Tips
* 🔑 **Tab Completion:** Type the first few letters of a folder or file name and hit the `Tab` key. The terminal will type the rest for you!
* ⬆️ **Arrow Keys:** Press the `Up Arrow` key to see the last command you typed. It saves a lot of re-typing.

---

## 🔗 Useful Links & Resources
* [Oh My Git!](https://ohmygit.org) — An interactive open-source game that teaches you Git visually.
* [GitHub Skills](https://github.com) — Free, interactive courses built directly into GitHub to practice using repositories.
* [Git Immersion](https://gitimmersion.com) — A guided tour that walks you through the fundamentals of Git step-by-step.
