Got it 👍 Here’s a clean **Git workflow** you can add to your `README.md` so anyone working on your project knows the steps:

---

# 🚀 Git Workflow

This project uses **Git** for version control. Follow the steps below to work with the repository.

## 1. Initialize Git

```bash
git init
```

## 2. Configure Git (only once per system)

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## 3. Check Status of Repository

```bash
git status
```

## 4. Add Files to Staging Area

* Add a specific file:

```bash
git add filename
```

* Add all files:

```bash
git add -A
```

## 5. Commit Changes

```bash
git commit -m "Your commit message"
```

## 6. Work with Branches

* Create a new branch:

```bash
git branch branch-name
```

* Switch to a branch:

```bash
git checkout branch-name
```

* Check current branch:

```bash
git branch
```

## 7. Merge Branches

Switch to the branch you want to merge into (e.g., master) and run:

```bash
git checkout master
git merge branch-name
```

## 8. View Commit History

```bash
git log
```

## 9. Push to Remote Repository (GitHub/GitLab)

* Add remote (only once):

```bash
git remote add origin https://github.com/username/repo.git
```

* Push changes:

```bash
git push origin branch-name
```

---

✅ This workflow ensures a smooth process of adding, committing, branching, and merging changes.

---

