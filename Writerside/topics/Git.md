# Git

## Basic Commands

**Check GIT version**
```bash
git --version
```

**Clone a repository**
```bash
git clone <repository_url>
```

**Initialize a new repository**
```bash
git init
```

**Check repository status**
```bash
git status
```

**Add files to staging area**
```bash
git add <file_name>
```

**Add all files to staging area**
```bash
git add .
```

**Commit changes**
```bash
git commit -m "<commit_message>"
```

**Push changes to the remote repository**
```bash
git push origin <branch_name>
```

**Pull the latest changes from the remote repository**
```bash
git pull
```

## Branching & Merging

**Create a new branch**
```bash
git checkout -b <branch_name>
```

**Switch to a branch**
```bash
git checkout <branch_name>
```

**List all branches**
```bash
git branch
```

**Merge a branch into the current branch**
```bash
git merge <branch_name>
```

**Delete a branch locally**
```bash
git branch -d <branch_name>
```

**Delete a branch remotely**
```bash
git push origin --delete <branch_name>
```

## Stashing & Cleaning

**Stash uncommitted changes**
```bash
git stash
```

**Apply stashed changes**
```bash
git stash apply
```

**List all stashes**
```bash
git stash list
```

**Drop a stash**
```bash
git stash drop
```

**Clean untracked files**
```bash
git clean -f
```

## Remote Repository Management

**Add a remote repository**
```bash
git remote add origin <repository_url>
```

**View remote repository URLs**
```bash
git remote -v
```

**Change the remote URL**
```bash
git remote set-url origin <new_repository_url>
```

**Remove a remote**
```bash
git remote remove <name>
```

## Miscellaneous

**View commit history**
```bash
git log
```

**View commit history with one-line summary**
```bash
git log --oneline
```

**Undo the last commit (keep changes in working directory)**
```bash
git reset --soft HEAD~1
```

**Hard reset to a specific commit**
```bash
git reset --hard <commit_hash>
```

**Check GIT configuration**
```bash
git config --list
```