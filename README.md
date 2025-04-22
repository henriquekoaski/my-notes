# 📝 My Notes

---

## 🔧 Git Commands

### 🛠️ Initialization & Configuration

```bash
git init                               # Start a new Git repository
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list                      # Show current Git config
```

---

### 📦 Cloning Repositories

```bash
git clone https://github.com/henriquekoaski/my-notes.git
```

---

### 🌳 Branching

```bash
git branch                             # List all branches
git branch my-branch                   # Create a new branch
git checkout my-branch                 # Switch to a branch
git checkout -b my-branch              # Create and switch to new branch
git merge my-branch                    # Merge a branch into the current one
```

---

### 💾 Staging & Committing

```bash
git status                             # Show current changes
git add .                              # Stage all changes
git add filename.ext                   # Stage a specific file
git commit -m "Your commit message"    # Commit staged changes
```

---

### 🔄 Pushing & Pulling

```bash
git push origin main                   # Push local changes to remote
git pull origin main                   # Pull latest changes from remote
```

---


### 🕵️ History & Logs

```bash
git log                                # View full commit history
git log --oneline                      # Compact commit history
git show <commit-hash>                 # Show changes of a specific commit
```

---

### 🔗 Remote Repositories

```bash
git remote -v                          # View configured remotes
git remote add origin <url>            # Add a new remote
```
