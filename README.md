# holbertonschool-zero_day

This repository is part of the **Zero Day** project at Holberton School, aimed at introducing students to **source code management** using **Git** and **GitHub**.

## 📚 Concepts Covered

- Source Code Management
- Git basics (clone, add, commit, push, pull, branch, merge)
- GitHub collaboration
- Branching and pull requests
- Writing professional README files and commit messages

---

## 🎯 Learning Objectives

By the end of this project, you will be able to explain:

- ✅ What is source code management
- ✅ The difference between Git and GitHub
- ✅ How to install and use Git from the command line
- ✅ How to create and use a GitHub repository
- ✅ How to write good `README.md` and commit messages
- ✅ How to stage, commit, push, and pull changes
- ✅ How to create and merge branches
- ✅ How to collaborate with others on a project
- ✅ Which files should be committed and which should be ignored

---

## 🧠 Resources Used

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/)
- [How to Write a Git Commit Message](https://cbea.ms/git-commit/)
- [Effective Pull Requests](https://google.github.io/eng-practices/review/reviewer/)
- [Branching Strategies](https://www.atlassian.com/git/tutorials/comparing-workflows)

---

## 🛠️ Project Tasks

### 0. Create and setup your Git and GitHub account

- Created a GitHub account
- Created a Personal Access Token
- Created a repository called `holbertonschool-zero_day`
- Added a README with “My first readme”
- Initial commit and push

### 1. Repo-session

- Created a `git/` directory
- Added a second `README.md` inside `git/` folder

### 2. Coding Fury Road

- Created folders: `bash/`, `c/`, `js/`
- Created files:
  - `bash/best` → contains:  
    ```bash
    #!/bin/bash
    echo "Best"
    ```
  - `bash/school` → contains:  
    ```bash
    #!/bin/bash
    echo "School"
    ```
  - `c/c_is_fun.c`
  - `js/index.js`, `js/main.js`

- Commit message: _“Starting to code today, so cool”_

### 3. Collaboration is the base of a company

- Created branch: `update_script`
- Modified:
  - `bash/best`: `echo "Best"` → `echo "Best School"`
  - `bash/school`: `echo "School"` → `echo "The school is open!"`
- Created file: `bash/98`
- Committed with: _“My personal work”_
- Switched to `main`
- Hotfix:
  - `bash/best`: `echo "This School is so cool!"`
  - Deleted folder: `js/`
- Commit message: _“Hot fix”_

### 4. Collaboration: be up to date

- **Used GitHub interface** to update `README.md` (this file)
- Pulled latest changes to local:
  ```bash
  git pull

🧪 Commands to Know

git clone <repo_url>
git add <file>
git commit -m "Your message"
git push origin <branch>
git pull
git branch <new_branch>
git checkout <branch>
git merge <branch>

📂 Repository Structure

holbertonschool-zero_day/
├── README.md
└── git/
    ├── README.md
    ├── bash/
    │   ├── best
    │   ├── school
    │   └── 98
    ├── c/
    │   └── c_is_fun.c
    ├── js/              (deleted during hotfix)
    └── up_to_date
