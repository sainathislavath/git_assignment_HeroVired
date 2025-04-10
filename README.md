# 🚀 Hero Vired Git Assignment

## 📁 Repository Name: `git_assignment_HeroVired`

This repository contains solutions for the Git assignment as part of the Hero Vired DevOps module. It demonstrates version control practices using branches, pull requests, Git LFS, collaboration, stash usage, and Python-based feature implementation.

---

## ✅ Q1: CalculatorPlus

### 🎯 Objective:
Enhance a Python calculator with a square root feature, handle divide-by-zero edge case, use proper Git workflows, and collaborate with a teammate.

### 📂 Branches Used:
- `main`
- `dev`
- `feature/sqrt`

### 🔧 Features Implemented:
- Basic arithmetic: Addition, Subtraction, Multiplication, Division
- Square root feature using `math.sqrt()`
- Bug fix in `divide()` to handle division by zero
- Created versioned releases: `v1.0` and `v2.0`

### 🔄 Git Workflow:
1. Created repo: `git_assignment_HeroVired`
2. Created `dev` branch from `main`
3. Added initial calculator code
4. Implemented `square_root` in `feature/sqrt`
5. Bug reported → hotfix made in `dev` (divide-by-zero)
6. Merged bugfix into `feature/sqrt` using `merge`
7. Pull request raised from `feature/sqrt` → `main`
8. Code reviewed by collaborator `kanakagarapati`
9. Final merge to `main`, version `v2.0` released

### 👥 Collaborator:
- GitHub Username: [`kanakagarapati`](https://github.com/kanakagarapati)

---

## ✅ Q2: Git LFS for Binary Files

### 🎯 Objective:
Use Git Large File Storage (LFS) to manage large binary files efficiently.

### 📂 Branch Used:
- `lfs`

### ⚙️ Steps Performed:
1. Installed Git LFS: `git lfs install`
2. Tracked `.zip` files using: `git lfs track "*.zip"`
3. Committed `.gitattributes`
4. Added a binary file > 200MB
5. Committed and pushed to GitHub
6. Cloned repository on another machine to verify LFS file download success

---

## ✅ Q3: GeometryCalculator

### 🎯 Objective:
Build a Python program with two features (circle & rectangle area calculation), use Git stash to manage parallel work on multiple branches.

### 📂 Branches Used:
- `geometry-calculator` (base)
- `feature/circle-area`
- `feature/rectangle-area`

### 🔄 Git Workflow:
1. Created `geometry-calculator` branch and added base code
2. Created `feature/circle-area`
   - Started implementation → stashed changes
3. Created `feature/rectangle-area`
   - Started implementation → stashed changes
4. Switched back to `feature/circle-area`
   - Applied stash → completed code → committed & pushed
5. Switched to `feature/rectangle-area`
   - Applied stash → completed code → committed & pushed
6. Created PRs for both → merged into `main` after review

---

## 🔍 Code Review

- Reviewer: [`kanakagarapati`](https://github.com/kanakagarapati/git_assignment_HeroVired)
- Reviewed their repository and approved their changes

---

## 📦 Releases

| Version | Description                           |
|---------|---------------------------------------|
| v1.0    | Initial release with arithmetic ops   |
| v2.0    | Added square root & divide bug fix    |

---

## 🧠 Tech Used

- 🐍 Python 3
- 🌳 Git & GitHub
- 🗂 Git Branching, Merging, PRs
- 💾 Git LFS
- 🧑‍🤝‍🧑 Collaboration & Code Review

---
