# GitHub Desktop Guide

This guide walks you through using GitHub Desktop to version and back up your code for class projects.

---

## 🌟 Why Use GitHub Desktop?

- Easy-to-use interface for Git and GitHub
- Helps you track changes without using the command line
- Ideal for individual projects or learning Git workflows

---

## 🧰 Initial Setup
Create a free GitHub account if you do not have one. Select Join for free. Follow the prompts to create your personal account or organization. You may want to use your personal email rather than school email. You will need to verify your email.  https://github.com/pricing 

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
   - Name: 
   - Local Path: For example navigate to your `GitHubRepos` folder
   - Language:  For example if setting up for Java
   - Initialize with .gitignore: For example ✅ Java
4. Click **Create Repository**
5. Click **Publish Repository** (Keep it private if it is class work!)

### 🔁 Clone an Existing Repository

1. File > Clone Repository
2. Choose from GitHub or URL
3. Select location in `GitHubRepos/`

---

## 🔄 Working with Changes

1. Open your project in your IDE (for example in Eclipse) and make code changes.
2. Go back to GitHub Desktop — your changed files will appear in the “Changes” tab.
3. Check the files you want to include in your commit.
4. Write a **commit summary** and (optionally) a longer description. ![commit](./images/github-dsktop_commit.png)
5. Click **Commit to main**.
6. Click **Push origin** to back up your work to GitHub. ![push](./images/github-dsktop-push.png)

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

## 💡 Tips and Best Practices

- Use github desktop to manage changes - commit, push, fetch, pull and do not use your IDE like Eclipse to manage the versions.
- Don’t use "Open in external editor" — instead, navigate to your repo manually 
- Use **View on GitHub** to confirm your commits are backed up.
- Use **Show in Finder/File Explorer** to locate your files on your computer.
- Commit and push often to avoid losing work.
  ![view and show](./github-dsktp-show-view.png)

---

## 🔗 Related Resources

- [Beginner GitHub Repo Setup](./beginner_git_hub_repo_setup.md)
- [Git & GitHub Cheat Sheet](./Git_GitHub_Cheat_Sheet.md)
- [GitHub Desktop Docs](https://docs.github.com/en/desktop)
- [How GitHub Can Be Used With a Team](https://www.youtube.com/watch?v=w3jLJU7DT5E ) 
