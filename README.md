# Git Add, Commit, and Push Demo

A small presentation project that demonstrates the three essential Git steps for saving and publishing changes.

## What this project demonstrates

1. **Add** — select files and stage them for the next commit.
2. **Commit** — save a snapshot with a clear message.
3. **Push** — upload local commits to GitHub.

## Quick demo

Run these commands in the project folder:

```bash
git status
git add .
git status
git commit -m "Add Git workflow demo"
git push origin main
```

If this is the first push for the current branch, use:

```bash
git push -u origin main
```

## Files

- [Presentation notes](PRESENTATION.md)
- [30–40 second video script](VIDEO-SCRIPT.md)
- [Git command reference](git-commands.txt)
- [Demo explanation](demo-note.txt)

## Important

This repository is a teaching example. The commands above are intended to be run in a local Git repository connected to this GitHub repository. The files being visible on GitHub does not, by itself, mean that a local `git add`, `git commit`, and `git push` was performed.

## Author

Prepared as a simple Git workflow demonstration.
