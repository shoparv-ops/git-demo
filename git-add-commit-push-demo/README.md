# Git Add, Commit, and Push Demo

A small, presentation-ready project for demonstrating the basic Git workflow with GitHub.

## What this demo shows

1. **Add** — stage changed files with `git add`.
2. **Commit** — save a snapshot with `git commit`.
3. **Push** — upload local commits to GitHub with `git push`.

## Requirements

- Git installed on your computer
- A GitHub account
- Access to this public repository

## 1. Clone the repository

Open Command Prompt, PowerShell, or a terminal and run:

```bash
git clone https://github.com/shoparv-ops/git-demo.git
cd git-demo/git-add-commit-push-demo
```

## 2. Make a change

Open `demo-note.txt`, add a short sentence, and save the file.

## 3. Check the changes

```bash
git status
```

Git should show `demo-note.txt` as modified.

## 4. Stage the change — git add

```bash
git add demo-note.txt
```

This stages the file so it will be included in the next commit.

Check the staging area:

```bash
git status
```

## 5. Commit the change

```bash
git commit -m "Update demo note"
```

A commit saves the staged changes in the local Git repository.

## 6. Push the commit to GitHub

```bash
git push origin main
```

This sends your local commit to the remote GitHub repository.

Refresh the repository page on GitHub to show the updated file.

## Important terms

| Term | Meaning |
|---|---|
| Working directory | Your local project files |
| Staging area | Changes selected for the next commit |
| Commit | A saved snapshot in Git history |
| Remote | The repository hosted on GitHub |
| Push | Uploading local commits to the remote |

## Quick workflow

```bash
git status
git add demo-note.txt
git status
git commit -m "Update demo note"
git push origin main
```

## Presentation tip

During the video, explain each command briefly and show the terminal output. Finish by refreshing GitHub and showing the new commit in the repository history.
