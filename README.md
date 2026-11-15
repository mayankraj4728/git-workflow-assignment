# Git & GitHub Workflow Demonstration & Test Case Design

**Student Name:** Mayank Raj  
**Student ID:** 2024eb02531  
**Student Email:** 2024eb02531@online.bits-pilani.ac.in  
**GitHub Email:** mayankraj4728@gmail.com  
**Institution:** BITS Pilani  
**Repository:** [https://github.com/mayankraj4728/git-workflow-assignment](https://github.com/mayankraj4728/git-workflow-assignment)  

---

## 📌 Project Overview
This repository contains the practical demonstration for **Question 1 (Git & GitHub Workflow)** of the Software Engineering / Version Control assignment. It showcases:
1. Local Git repository initialization with `index.html` and `about.html`.
2. Sequential commit history tracking revisions.
3. Feature branch creation (`feature`), isolated development, and non-fast-forward merge (`--no-ff`) back into `main`.
4. Git ignore rules configuration (`.gitignore`) ignoring `*.log` files and `temp/` folder.
5. Local commit undo operation using `git reset HEAD~1` with repository state verification.
6. Remote GitHub synchronization of `main` and `feature` branches.
7. Complete command reference in [`git_commands.txt`](./git_commands.txt).

---

## 🌳 Commit History Graph
```bash
* 578b53f (HEAD -> main, origin/main) docs: add comprehensive README.md
* ab0665d docs: add git_commands.txt documenting all git commands with explanations
* e89c140 chore: add .gitignore to ignore *.log files and temp/ directory
*   aae87ae Merge branch 'feature' into main
|\  
| * 0f1c885 (origin/feature, feature) feat(about): Add team information and mission section on feature branch
|/  
* b5e4b51 Update index.html: Add navigation bar, hero section, and footer
* 1672645 Initial commit: Add index.html and about.html
```

---

## 📂 Repository Structure
```
git-workflow-assignment/
├── .gitignore           # Ignores *.log and temp/
├── about.html           # About page with team & mission
├── git_commands.txt     # Complete command documentation with explanations
├── index.html           # Home page with navigation and hero section
└── README.md            # Repository overview and documentation
```

---

## 🧪 Question 2: Test Case Design Summary
The assignment also includes comprehensive Black-Box Test Case Design for a **Login System** covering:
- Equivalence Partitioning & Boundary Value Analysis (Password length < 6, = 6, > 6)
- Empty username and password validations
- State transition testing: 3 consecutive failed attempts leading to account lockout
- The complete test specification is documented in the final submission report PDF.
