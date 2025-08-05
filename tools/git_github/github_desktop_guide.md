# GitHub Desktop Guide

This guide walks you through using GitHub Desktop to version and back up your code for class projects.

---

## 🌟 Why Use GitHub Desktop?

- Easy-to-use interface for Git and GitHub
- Helps you track changes without using the command line
- Ideal for individual projects or learning Git workflows

---

## 🧰 Initial Setup

1. **Download GitHub Desktop**  
   https://desktop.github.com

2. **Sign in to GitHub**  
   Use your GitHub account.

3. **Create a Folder for Repositories**  
   - Recommended: `C:/GitHubRepos/` (Windows) or `~/Documents/GitHubRepos/` (Mac)
   - Avoid syncing with OneDrive or iCloud

---

## 📁 Create or Clone a Repository

### ✅ Create a New Repository

1. Open GitHub Desktop
2. Click **File > New Repository**
3. Fill in:
   - Name: `CS1050_Spring2025`
   - Local Path: Navigate to your `GitHubRepos` folder
   - Language: Java
   - Initialize with .gitignore: ✅ Java
4. Click **Create Repository**
5. Click **Publish Repository** (Keep it private!)

### 🔁 Clone an Existing Repository

1. File > Clone Repository
2. Choose from GitHub or URL
3. Select location in `GitHubRepos/`

---

## 🔄 Working with Changes

1. Open your project in Eclipse and make code changes.
2. Go back to GitHub Desktop — your changed files will appear in the “Changes” tab.
3. Check the files you want to include in your commit.
4. Write a **commit summary** and (optionally) a longer description.
5. Click **Commit to main**.
6. Click **Push origin** to back up your work to GitHub.

> 🧠 *Note:* When you check files to include in a commit, this is technically called “staging” in Git, but GitHub Desktop keeps it simple and doesn’t use that term.

---

## 🔄 Fetch vs Pull

When changes are made on GitHub.com (for example, editing `.gitignore`):

- **Fetch**: Checks if there are changes available on GitHub.
- **Pull**: Brings those changes into your local files.

Typical workflow:
1. Click **Fetch origin**
2. Then click **Pull origin**

---

## 📂 Organizing Folders in Your Repository

Recommended folders:
- `Assignments/` — your assignment source files and documents
- `EclipseWorkspace/` — Eclipse projects
- `ClassResources/` — course lecture slides, examples, etc.
- `TechDocs/` — technical documentation

---

## 💡 Tips and Best Practices

- Don’t use "Open in external editor" — instead, navigate to your repo manually in Eclipse or your IDE.
- Use **View on GitHub** to confirm your commits are backed up.
- Use **Show in Finder/File Explorer** to locate your files on your computer.
- Commit and push often to avoid losing work.

---

## 🔗 Related Resources

- [Beginner GitHub Repo Setup](./beginner_git_hub_repo_setup.md)
- [Git & GitHub Cheat Sheet](./Git_GitHub_Cheat_Sheet.md)
- [GitHub Desktop Docs](https://docs.github.com/en/desktop)
