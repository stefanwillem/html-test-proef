# Git Cheat Sheet

A quick reference for the most commonly used Git commands.

---

## git status

Shows the current state of your working directory and staging area.

```bash
git status
```

**Example:** Check which files have been modified before committing.

```bash
git status
```

---

## git branch

Lists all local branches in your repository.

```bash
git branch
```

**Example:** See which branch you are currently on (marked with `*`).

```bash
git branch
```

---

## git switch

Switches to an existing branch.

```bash
git switch <branch-name>
```

**Example:** Move to the `main` branch.

```bash
git switch main
```

---

## git switch -c

Creates a new branch and switches to it immediately.

```bash
git switch -c <branch-name>
```

**Example:** Create and switch to a feature branch.

```bash
git switch -c feature/login
```

---

## git checkout

Switches branches or restores files (older alternative to `git switch`).

```bash
git checkout <branch-name>
```

**Example:** Switch to the `develop` branch.

```bash
git checkout develop
```

---

## git checkout -b

Creates a new branch and checks it out in one step.

```bash
git checkout -b <branch-name>
```

**Example:** Create and switch to a new branch for a bug fix.

```bash
git checkout -b fix/nav-menu
```

---

## git add .

Stages all changed and new files in the current directory for the next commit.

```bash
git add .
```

**Example:** Stage every modified file before committing.

```bash
git add .
```

---

## git commit -m "Describe your changes"

Saves your staged changes as a new commit with a descriptive message.

```bash
git commit -m "Describe your changes"
```

**Example:** Commit your work with a clear message.

```bash
git commit -m "Add contact form to homepage"
```

---

## git push

Uploads your local commits to the remote repository.

```bash
git push
```

**Example:** Send your latest commits to the remote.

```bash
git push
```

---

## git push -u origin <branch-name>

Pushes a branch to the remote and sets it as the upstream tracking branch.

```bash
git push -u origin <branch-name>
```

**Example:** Push a new branch and link it to the remote.

```bash
git push -u origin feature/login
```

---

## git pull

Downloads changes from the remote repository and merges them into your current branch.

```bash
git pull
```

**Example:** Update your local branch with the latest remote changes.

```bash
git pull
```

---

## git fetch

Downloads the latest changes from the remote without merging them into your branch.

```bash
git fetch
```

**Example:** See what changed on the remote before merging.

```bash
git fetch
```

---

## git merge

Combines changes from another branch into your current branch.

```bash
git merge <branch-name>
```

**Example:** Merge a feature branch into `main`.

```bash
git merge feature/login
```

---

## git log

Displays the full commit history for the current branch.

```bash
git log
```

**Example:** Review recent commits with authors, dates, and messages.

```bash
git log
```

---

## git log --oneline

Shows a compact, one-line summary of each commit.

```bash
git log --oneline
```

**Example:** Quickly scan recent commits in a short format.

```bash
git log --oneline
```

---

## git branch

Lists all local branches in your repository.

```bash
git branch
```

**Example:** Confirm which branches exist locally.

```bash
git branch
```

---

## git branch -a

Lists all local and remote branches.

```bash
git branch -a
```

**Example:** View every branch, including those on the remote.

```bash
git branch -a
```

---

## git branch -d

Deletes a local branch that has already been merged.

```bash
git branch -d <branch-name>
```

**Example:** Remove a merged feature branch.

```bash
git branch -d feature/login
```

---

## git branch -D

Force-deletes a local branch, even if it has not been merged.

```bash
git branch -D <branch-name>
```

**Example:** Remove a branch you no longer need.

```bash
git branch -D experiment/old-idea
```

---

## git clone

Creates a local copy of a remote repository.

```bash
git clone <repository-url>
```

**Example:** Download a project from GitHub to your computer.

```bash
git clone https://github.com/username/repository.git
```

---

# Git Workflow

A simple day-to-day workflow for saving and sharing your changes:

```bash
git status
```

Check what files have changed before you commit.

```bash
git add .
```

Stage all your changes for the next commit.

```bash
git commit -m "Describe your changes"
```

Save your staged changes with a clear commit message.

```bash
git push
```

Upload your commits to the remote repository.

---

# Local Development Server

Start a simple local web server to preview your site in the browser:

```bash
python3 -m http.server 8000
```

This starts a local web server on port 8000 so you can view your files at `http://localhost:8000`.

To stop the running server, press:

```
Ctrl + C
```

This stops the server and returns you to the command prompt.
