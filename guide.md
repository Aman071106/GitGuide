# Git Guide 🧠

A beginner-friendly guide to understanding and practicing basic Git commands and remote repository management.

---

## 📦 Basic Setup

Start by watching a [Git Basics video](#) *(insert actual link if needed)* to understand the foundation.

---

## 🧰 Essential Git Commands

### 🔧 Initialization and Cloning

* `git init`
  Initialize a new Git repository in your local folder.

* `git clone <repo-url>`
  Clone an existing remote repository to your local system.

---

### 🔄 Remote Syncing

* `git pull`
  Fetch and merge changes from the remote repository.

* `git push`
  Upload local commits to the remote repository.

* `git fetch`
  Download changes from the remote repo but don’t merge.

---

### 📋 Staging and Committing

* `git add <filename>`
  Stage a file for commit.

* `git commit -m "message"`
  Commit staged changes with a message.

* `git restore --staged <filename>`
  Unstage a file (undo `git add`).

* `git reset <filename>`
  Also unstages a file, similar to above.

---

## 🌿 Working with Branches

* `git branch`
  List all branches. *(Note: Shows empty output until at least one commit is made.)*

* `git branch -M <new-name>`
  Rename the current branch.

* `git checkout -b <branch-name>`
  Create and switch to a new branch.

---

## 🌐 Managing Remotes

* Add a new remote:

  ```bash
  git remote add <alias> https://github.com/your-username/your-repo.git
  ```

* View all remotes:

  ```bash
  git remote -v
  ```

* Remove redundant remote:

  ```bash
  git remote remove <alias>
  ```

🔀 *You can have multiple folders on your system connected to the same remote repo.*

---

## 🧱 Exploring Remote Commits

At any commit on GitHub, you can click the `<>` icon on the right to browse the repository at that point in history.

---

## 📁 Extra Notes

* A Git repo will not show any branches until **at least one commit** is made.
* Keep remote aliases minimal to avoid confusion (`codespace1`, `origin`, etc.).

---


