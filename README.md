# 📚 GitHub Group Task (Fork Workflow)

Welcome to the GitHub Group Task! 🎯  
This exercise will help you practice working with **forks, branches, and Pull Requests (PRs)** — the standard workflow for collaborating on GitHub projects.

---

## 📝 Task Overview

You will:

1. **Fork** this repository to your GitHub account.
2. **Clone** your fork locally.
3. Make changes on a **new branch**.
4. **Commit** and **push** your changes to your fork.
5. **Create a Pull Request (PR)** from your fork to the original repository.

This workflow simulates how open-source contributions work in the real world.

---

## 🛠 Step-by-Step Instructions

### 1. Fork the repository

- Go to the GitHub repository in your browser.
- Click the **Fork** button (top-right corner).
- You now have a copy of the repository in your own GitHub account.

---

### 2. Clone your fork locally

Open your terminal and run:

```bash
git clone https://github.com/<YOUR-GITHUB-USERNAME>/<REPO-NAME>.git
cd <REPO-NAME>
````

> Replace `<YOUR-GITHUB-USERNAME>` with your GitHub username.

---

### 3. Create a new branch

Before making changes, create a branch named after you:

```bash
git checkout -b yourname-task
```

> Example: `git checkout -b yonas-task`

---

### 4. Make your changes

* Open the files in your favorite code editor.
* Edit the `CONTRIBUTORS.md` file (create it if it doesn’t exist) and add:

  * Your **name**
  * A short **description of your contribution**
* You can also make small edits to other files, as instructed.

---

### 5. Stage and commit your changes

```bash
git add .
git commit -m "Add <yourname> contribution"
```

> Tip: Use clear commit messages.
> Example: `git commit -m "Add Yonas Girma to CONTRIBUTORS.md"`

---

### 6. Push your branch to your fork

```bash
git push origin yourname-task
```

---

### 7. Create a Pull Request (PR)

* Go to your fork on GitHub.
* Click the **Compare & pull request** button for your branch.
* Make sure the **base repository** is the original repository, and the **base branch** is `main`.
* Write a **short description** of your changes.
* Click **Create Pull Request**.

---

## ✅ Checklist Before PR

* [ ] Changes are complete and tested locally.
* [ ] Commit message is clear.
* [ ] Branch is pushed to your fork.
* [ ] PR description clearly explains your changes.

---

## 🏆 Goals

* Learn how to **fork, clone, branch, commit, push, and PR**.
* Practice **collaborating in a safe workflow**.
* Experience **real-world open-source contribution workflow**.

---

## 🔗 Useful Resources

* [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
* [GitHub Forking Workflow](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
* [Creating a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

---

💡 **Tip:** If you get stuck, use:

```bash
git status
git log --oneline
```

These commands help you understand your current state and history.

---
