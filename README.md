# 🚀 GitHub for Absolute Beginners

Welcome! This guide is made for anyone starting their journey with GitHub. Whether you're a solo developer, a student, or a collaborator, this will teach you how to use GitHub effectively from scratch.

---

## 📖 Table of Contents
1. [What Is Git and GitHub](#-what-is-git-and-github)
2. [Creating a Repository](#-creating-a-repository)
3. [Managing Your Repository](#-managing-your-repository)
4. [Understanding Branches](#-understanding-branches)
5. [Making a Pull Request](#-making-a-pull-request)
6. [Working with Issues](#-working-with-issues)
7. [GitHub Social Features](#-github-social-features)
8. [Essential Git Commands](#-essential-git-commands)
9. [Learning Resources](#-learning-resources)

---

## 🔧 What Is Git and GitHub?

- **Git** is a version control system that tracks changes in your code over time.
- **GitHub** is a cloud-based platform that lets you host your Git repositories and collaborate with others.

### Why use them?
- Keep history of all your changes
- Collaborate with teams
- Roll back to previous versions
- Work on multiple features at once (branches)

---

## 📦 Creating a Repository

1. Go to [https://github.com](https://github.com)
2. Click the **+ icon** at the top-right > **New repository**
3. Fill in the following:
   - **Repository name**: e.g. `my-first-repo`
   - **Description** (optional)
   - **Visibility**: Public (visible to all) or Private (only you or team)
   - ✅ Add README (optional)
   - ✅ Add .gitignore (optional, choose language)
   - ✅ Add License (optional)
4. Click **Create repository**

---

## 🛠 Managing Your Repository

### 🔄 Renaming a Repo
1. Go to the repo
2. Click on **Settings**
3. Under **Repository name**, edit the name

### 🔐 Changing Visibility (Private/Public)
1. Go to **Settings**
2. Scroll to **Danger Zone**
3. Click **Change repository visibility**

### 🗑 Deleting a Repo
1. Go to **Settings**
2. Scroll to **Danger Zone**
3. Click **Delete this repository** and confirm

### 🔼 Updating Code in Repo
```bash
# Clone repo
git clone https://github.com/username/repo-name.git

# Make your changes locally
git add .
git commit -m "Describe your update"
git push
```

---

## 🌿 Understanding Branches

Branches allow you to work on different features or fixes without disturbing the main codebase.

### 🔀 When to Use Branches
- Adding a new feature
- Fixing a bug
- Testing something risky

### 🧪 Example Workflow
```bash
# Start from main
git checkout main

# Create and switch to new branch
git checkout -b feature/login-page

# Make changes
git add .
git commit -m "Add login page"

# Push to GitHub
git push origin feature/login-page
```

---

## 🔁 Making a Pull Request (PR)

A Pull Request is a way to propose your changes to be merged into another branch (usually `main`).

### ✅ You *can* make PRs in your **own repo**

### Step-by-step:
1. Push your branch to GitHub
2. Go to the repo → Click **"Compare & pull request"**
3. Fill out:
   - Title
   - Description
   - Base branch (e.g., `main`)
   - Compare branch (your feature branch)
4. Click **Create Pull Request**
5. Optionally: Review code, discuss changes
6. Click **Merge pull request**

---

## 🐛 Working with Issues

Issues are used to track bugs, ideas, and tasks.

### Create an Issue:
1. Go to the **Issues** tab in your repo
2. Click **New issue**
3. Add a:
   - Title
   - Description
   - Labels (bug, feature, etc.)
   - Assignees
   - Milestones (optional)

### Close issues automatically in commits:
```bash
git commit -m "Fix login error, closes #45"
```

---

## ⭐ GitHub Social Features

- **Star** ⭐: Bookmark or show support for a repo
- **Watch** 👀: Get notifications for activity
- **Fork** 🍴: Create your own copy of someone else's repo
- **Pull Request** 🔁: Propose changes to another repo
- **Contributions** ✅: All your commits, issues, PRs tracked on your profile

---

## 🧪 Essential Git Commands

| Command | Description |
|--------|-------------|
| `git status` | See current changes |
| `git add .` | Stage all files |
| `git commit -m "message"` | Save changes with message |
| `git push` | Send changes to GitHub |
| `git pull` | Get updates from GitHub |
| `git checkout branch-name` | Switch branches |
| `git checkout -b new-branch` | Create new branch |
| `git merge branch-name` | Merge into current branch |
| `git clone URL` | Download a repo |

---

## 📚 Learning Resources

- 🔗 [GitHub Learning Lab](https://lab.github.com)
- 📘 [Pro Git Book](https://git-scm.com/book/en/v2)
- 🧪 [Try Git (Interactive)](https://try.github.io)
- 📺 [Git & GitHub Crash Course (YouTube)](https://www.youtube.com/watch?v=RGOj5yH7evk)

---

## 💡 Pro Tip:
Start your own GitHub repo with this README and begin learning by:
- Editing this file
- Creating branches
- Making pull requests
- Opening and closing issues
