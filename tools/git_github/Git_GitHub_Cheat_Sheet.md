## Essential Git & GitHub Commands

Below is a quick reference for working with Git and GitHub in a student-friendly development workflow.

| **Command / Action** | **What It Does** |
|----------------------|------------------|
| `git clone <repo-url>` | Makes a full copy of the GitHub repo on your computer or VS Code environment. |
| `git status` | Shows what files have changed and what’s ready to commit. |
| `git branch` | Lists all branches in your local repository. |
| `git branch <new-branch-name>` | Creates a new branch to work in safely without touching `main`. |
| `git checkout <branch-name>` | Switches to a different branch. |
| `git checkout -b <new-branch-name>` | Creates and switches to a new branch in one step. |
| `git add .` | Stages all changed files so they’re ready to commit. |
| `git commit -m "Your message"` | Saves a snapshot of your staged changes with a descriptive message. |
| `git push origin <branch-name>` | Uploads your local branch and commits to GitHub. |
| `git log` | Shows the history of commits in the current branch. |
| **(GitHub) Pull Request** | A request to merge your branch changes into the `main` branch after review. |
| **(GitHub) Merge** | Combines your changes into `main` after a pull request is approved. |

---

### 🔀 Concepts

- **Clone**: `git clone <repo-url>`  
  Makes a local copy of a repository from GitHub.

- **Status**: `git status`  
  Shows current changes, staged files, and branch info.

- **Commit**: `git commit -m "Message"`  
  Records a snapshot of your changes to the repo history.

- **Push**: `git push origin <branch-name>`  
  Sends your local commits to GitHub.

- **Pull**: `git pull origin <branch-name>`  
  Updates your local branch with the latest from GitHub.

- **Fork**:  
  A personal copy of someone else's repository on GitHub. You can modify it without affecting the original.

- **Branch**:  
  A separate line of development, useful for adding features or fixes without affecting `main`.

- **Merge**:  
  Combines changes from one branch into another, often done through a pull request.

