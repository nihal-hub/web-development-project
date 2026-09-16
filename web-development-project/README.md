# Web Development Project

Git and GitHub assignment project.

## Git Workflow

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
git config --global --list

git init
git status
git add .
git commit -m "Initial commit"
git status
```

Create a **Public** GitHub repository named `web-development-project`, then:

```bash
git remote add origin https://github.com/YOUR-USERNAME/web-development-project.git
git remote -v
git branch -M main
git push -u origin main
```

Make a small change to `index.html`, then:

```bash
git status
git add .
git commit -m "Update project"
git push
```
