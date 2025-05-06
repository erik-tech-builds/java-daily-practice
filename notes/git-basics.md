# Git Basics
github.com/git-guides

This document contains quick reference commands for Git.

---

## Common Commands

| Command | Actions |
|---------|---------|
| 'git init' | Initialize a Git repo |
| 'git status' | Check repo status |
| 'git add file' or 'git add .' | Add file(s) to staging area |
| 'git commit -m "message"' | Commit a snapshot of repository |
| 'git log' | View commit history |
| 'git branch -M main' | Rename branch to 'main' |
| 'git config --list | List current git config |
| 'git config --help | List options/syntax for git config |

---

## Remote Commands

| 'git pull origin main' | Pull remote branch main into local branch |
| 'git push origin main' | Push local commit to remote repository |

---

## Branching Commands

| 'git branch -M newName' | Rename remote branch to 'newName' |
| 'git branch newBranch' | Created branch 'newBrance' |
| 'git branch' | List local branched, indicating current branch |
| 'git checkout newBranch' | Make 'newBranch' the current branches | 
| 'git checkout -b otherBranch' | Create and checkout 'otherBranch' |

## Tips

- Write clear commit messages ex: 'git commit -m "Added new OOP method example"'
- Pull often to ensure updated on local working branch. Before commits and starting work. ex: 'git pull'
- Push often to save progress! Updates remote branch with local commits. ex: 'git push'
- NEVER PUSH BROKEN CODE


---

> "Pull Frequently, Commit Often, Push Early!





