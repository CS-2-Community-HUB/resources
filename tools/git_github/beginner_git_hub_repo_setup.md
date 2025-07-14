## 🧰 Beginner Guide: Setting Up a GitHub Repository

This guide explains the main ways to start a project on GitHub and introduces the role of `.gitignore`.

---

### 🚀 1. Ways to Create a Repository

#### ✅ Option A: Create on GitHub.com

- Easiest way to start a new project
- Auto-generates a README and optional `.gitignore`
- Clone to your computer later

**Steps:**

1. Click the **+** icon in the top right > **New repository**
2. Name your repo and choose visibility (public/private)
3. (Optional) Add README, `.gitignore`, license
4. Click **Create repository**

#### ✅ Option B: Create Locally with Git

- Good for coding offline or starting with existing files
- Create the repo locally, then push to GitHub

```bash
mkdir my-project
cd my-project
git init
echo "# My Project" > README.md
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/my-project.git
git push -u origin main
```

#### ✅ Option C: Fork an Existing Repo

- Use this when contributing to another project
- Creates a copy of someone else's repo under your account

**Steps:**

1. Go to the original repo
2. Click **Fork** (top right)
3. It appears in your GitHub as your own copy
4. Clone it and work on changes

---

### 📂 What Is a `.gitignore` File?

A `.gitignore` tells Git which files/folders **not to track**.

Example contents:

```bash
# macOS system files
.DS_Store

# Python cache
__pycache__/
*.pyc

# VS Code settings
.vscode/
```

**Why use it?**

- Prevents committing junk or sensitive files
- Keeps repos clean and focused on source code

You can use a [GitHub-provided template](https://github.com/github/gitignore) when creating the repo, or create your own locally.

---
## Pushing Changes, Branching & Pull Requests

### Push Changes to GitHub

After editing files:

```bash
git add .
git commit -m "Describe your changes"
git push origin main
```

If you're working on a branch:

```bash
git push origin branch-name
```

---

### 🌐 Create and Switch to a New Branch

```bash
git checkout -b feature/my-feature-name
```

Make your changes on this branch. Then push it:

```bash
git push origin feature/my-feature-name
```

---

### Open a Pull Request (PR)



1. Go to your repo on GitHub
2. Click the "Compare & pull request" button
3. Write a descriptive title and description
4. Click **Create pull request**

### 👋 Open a Pull Request (PR)

1. Go to your repo on GitHub
2. Click the "Compare & pull request" button
3. Write a descriptive title and description
4. Click **Create pull request**



#### 🧾 What Does a Pull Request Do?

A **Pull Request (PR)** is a formal request to merge changes from one branch (often a feature branch) into another (usually `main`).

- It shows the difference between the two branches.
- Others can **review**, **comment**, or **request changes** before approving.
- Once approved, your work can be safely merged into the main project.

> ✅ Pull Requests help maintain clean, reviewed, and collaborative code — especially in group projects.



