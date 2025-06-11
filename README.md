# 🚀 Git Cheatsheet: Master Version Control with Ease! 🌟

Welcome to the **Ultimate Git Cheatsheet**! Whether you're a beginner or a seasoned developer, this concise guide will help you navigate Git commands like a pro. From initializing repositories to managing branches and collaborating with teams, we've got you covered. Let's dive into the world of version control! 🎉

---

## 📋 Table of Contents
- [🚀 Git Cheatsheet: Master Version Control with Ease! 🌟](#-git-cheatsheet-master-version-control-with-ease-)
  - [📋 Table of Contents](#-table-of-contents)
  - [🌱 Getting Started](#-getting-started)
  - [🛠 Basic Commands](#-basic-commands)
  - [🌿 Branching \& Merging](#-branching--merging)

---

## 🌱 Getting Started
Set up your Git environment and start tracking your projects.

- **Install Git**: Download and install from [git-scm.com](https://git-scm.com/).
- **Configure Git**:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
- **Initialize a Repository**:
  ```bash
  git init
  ```
- **Clone a Repository**:
  ```bash
  git clone <repository-url>
  ```

---

## 🛠 Basic Commands
Manage your files and commits with these essential commands.

- **Check Status**:
  ```bash
  git status
  ```
- **Add Files**:
  ```bash
  git add <file>          # Add specific file
  git add .               # Add all changes
  ```
- **Commit Changes**:
  ```bash
  git commit -m "Your commit message"
  ```
- **View Commit History**:
  ```bash
  git log
  ```

---

## 🌿 Branching & Merging
Work on features or fixes without affecting the main codebase.

- **Create a Branch**:
  ```bash
  git branch <branch-name>
  ```
- **Switch to a Branch**:
  ```bash
  git checkout <branch-name>
  ```
- **Create and Switch to a Branch**:
  ```bash
  git checkout -b <branch-name>
  ```
- **Merge a Branch**:
  ```bash
  git checkout main
  git merge <branch-name>
  ```
- **Delete a Branch**:
  ```bash
  git branch -d <branch-name>
  ```

---