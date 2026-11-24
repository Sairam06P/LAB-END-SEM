# Git Merge Lab

Open index.html in a browser. This repository demonstrates branching and merging.

## Verify

```bash
git branch
git log --oneline --graph --all
git status
```

The feature-about branch was merged into main using --no-ff.

## Experiment details

The website includes the aim, tools, learning objectives, Git concepts, procedure, merge types, command reference, actual merge history, inference and result. CSS is embedded in index.html; no dependencies are required.

## Publish to GitHub

For an empty remote repository, add its URL as origin and run `git push -u origin main` followed by `git push --all origin`. If origin already exists, use `git remote set-url origin URL` instead. Do not force-push over unrelated history.
