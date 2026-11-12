# Git Add, Commit, and Push

## Goal

Explain how changes move from a working directory to a GitHub repository.

## 1. Git Add

Command:

```bash
git add .
```

This stages the changed files. Staging means selecting which changes will be included in the next commit.

## 2. Git Commit

Command:

```bash
git commit -m "Add Git workflow demo"
```

A commit saves a snapshot of the staged changes in the local Git repository. The message briefly describes the change.

## 3. Git Push

Command:

```bash
git push origin main
```

Push sends local commits to the remote repository on GitHub.

## How the steps fit together

Working directory → Staging area → Local repository → Remote repository (GitHub)

- `git add`: working directory to staging area
- `git commit`: staging area to local repository
- `git push`: local repository to GitHub

## Demo checklist

1. Open the project folder in the terminal.
2. Run `git status` to inspect changes.
3. Run `git add .`.
4. Run `git status` again to show staged changes.
5. Run `git commit -m "Add Git workflow demo"`.
6. Run `git push origin main`.
7. Refresh GitHub and show the uploaded commit and files.

## Conclusion

Add selects changes, commit records them locally, and push publishes those commits to GitHub.
