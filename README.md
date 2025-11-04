````markdown
# 📚 GitHub Group Task

Welcome to the GitHub Group Task! 🎯  
This exercise will help you practice using Git and GitHub collaboratively, including cloning a repository, making changes locally, and submitting a Pull Request (PR).

---

## 📝 Task Overview

You will:

1. **Clone** this repository to your local machine.
2. Make some **changes** to the files (instructions below).
3. **Commit** your changes.
4. **Push** the changes to your fork or branch.
5. **Create a Pull Request (PR)** so your changes can be reviewed.

This will simulate a real-world team workflow using Git and GitHub.

---

## 🛠 Task Instructions

1. **Clone the repository**

   Open your terminal and run:

   ```bash
   git clone https://github.com/<YOUR-USERNAME>/<REPO-NAME>.git
   cd <REPO-NAME>
````

2. **Create a new branch**

   Before making changes, create a branch named after you:

   ```bash
   git checkout -b yourname-task
   ```

   > Example: `git checkout -b yonas-task`

3. **Make your changes**

   * Open the files in your favorite code editor.
   * Add your name and a short description of your contribution in the `CONTRIBUTORS.md` file (create it if it doesn’t exist).
   * Add a simple message or edit in the `example.txt` file (or any file I specify).

4. **Stage and commit your changes**

   ```bash
   git add .
   git commit -m "Add <yourname> contribution"
   ```

   > Tip: Use meaningful commit messages. For example: `git commit -m "Add Yonas Girma details to CONTRIBUTORS.md"`

5. **Push your branch to GitHub**

   ```bash
   git push origin yourname-task
   ```

6. **Create a Pull Request (PR)**

   * Go to the GitHub repository in your browser.
   * You’ll see a button like `Compare & pull request` for your branch.
   * Click it and write a **short description** of your changes.
   * Submit the PR for review.

---

## ✅ Checklist Before PR

* [ ] Code or file changes are complete
* [ ] Commit message is meaningful
* [ ] Branch is pushed to GitHub
* [ ] PR description clearly explains your changes

---

## 🏆 Goals

* Learn how to **clone**, **edit**, **commit**, **push**, and **PR** on GitHub.
* Experience **branching workflows**.
* Practice writing **clean commits and descriptions**.
* Collaborate as a team using GitHub.

---

## 🔗 Useful Resources

* [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
* [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow)
* [Creating a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

---

💡 **Tip:** If you get stuck, always check `git status` and `git log` to understand what’s happening.

---
