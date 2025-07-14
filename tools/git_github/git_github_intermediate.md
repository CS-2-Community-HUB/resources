## 🚀 Intermediate Git & GitHub Concepts

This section covers intermediate Git skills useful for students who have mastered the basics and are ready to collaborate on real projects.

---

### 🧪 Branching Best Practices

- Use meaningful branch names:
  ```bash
  git checkout -b feature/add-signup-form
  ```

- Keep branches focused on one task or feature.

- Always branch from the latest `main`:
  ```bash
  git checkout main
  git pull origin main
  git checkout -b fix/navbar-bug
  ```

---

### 🔁 Rebasing vs Merging

- `git merge` keeps a full history (safer, easier for beginners).
- `git rebase` creates a linear history (cleaner but riskier).

> ✅ Recommendation: **Use `merge` for team projects unless you're confident with `rebase`.**

---

### 👀 Reviewing Commits

View a list of commits:
```bash
git log --oneline
```

View changes introduced by a specific commit:
```bash
git show <commit-hash>
```

---

### ♻️ Reverting to a Previous Version

#### Undo Local Changes (Before Commit)
Discard edits and go back to the last committed version:
```bash
git restore <filename>
# or for all files:
git restore .
```

#### Undo the Last Commit (Keep Changes Locally)
Undo the most recent commit but keep file changes:
```bash
git reset --soft HEAD~1
```

#### Remove the Last Commit Completely (Dangerous!)
```bash
git reset --hard HEAD~1
```
> ⚠️ This deletes the last commit and all changes. Use with caution.

#### Revert a Commit Safely (Best for Shared Branches)
Creates a new commit that undoes a previous one:
```bash
git revert <commit-hash>
```
Find commit hashes using:
```bash
git log
```

> ✅ Best practice: make a new branch before experimenting:
```bash
git checkout -b revert-test
```

---

### 🌐 GitHub Pull Request Tips

- Add a descriptive title: `Fix broken footer in mobile view`
- Use checklists and link related issues (e.g., "Closes #5")
- Review your diff before submitting!
- Ask for feedback and be open to changes

---

### 🧠 Pro Tip: Aliases for Speed

Add shortcuts to your `.gitconfig`:
```bash
[alias]
  co = checkout
  br = branch
  ci = commit
  st = status
  lg = log --oneline --graph --all
```
Then run:
```bash
git co main
```

---



