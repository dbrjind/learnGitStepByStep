# 📘 Daily Learning Diary

This file contains my daily learning progress for the first week of my Git & GitHub journey.

---

## **Day 1 — 2025-12-13: Git & GitHub Basics**

### **1. Set up Git**

* Installed Git on my local machine.
* Configured user details:

  ```bash
  ```

git config --global user.name "My Name"
git config --global user.email "[me@example.com](mailto:me@example.com)"
git config --global init.defaultBranch main

````
- Generated SSH key and added it to GitHub.

### **2. Created a GitHub Repository**
- Created a new repository using GitHub web UI.

### **3. Cloned the Repository Locally**
```bash
git clone git@github.com:username/my-diary.git
cd my-diary
````

### **4. Added a New File**

```bash
mkdir diary
echo "2025-12-13: Learned Git basics" > diary/2025-12-13.md
git add diary/2025-12-13.md
```

### **5. Committed the Changes**

```bash
git commit -m "Add diary entry for 2025-12-13: Git basics"
```

### **6. Pushed the Changes**

```bash
git push -u origin main
```

---

## **Day 2 — Introduction to Branching**

* Topic: Learned how to create and switch branches in Git.
* Commands practiced:

  ```bash
  git branch feature/test
  git checkout feature/test
  git switch -c experiment
  ```
* Notes: Understood why branches are useful for isolating work.

## **Day 3 — Understanding Git Status & Git Diff**

* Topic: Explored how Git tracks changes.
* Commands practiced:

  ```bash
  git status
  git diff
  git diff --staged
  ```
* Notes: Learned difference between working directory, staging area, and committed history.

## **Day 4 — Working With .gitignore**

* Topic: Learned how to ignore specific files and folders.
* Examples added:

  ```
  node_modules/
  .DS_Store
  *.log
  ```
* Notes: Helps keep unwanted files out of the repository.

## **Day 5 — GitHub Pull Requests (PRs)**

* Topic: Learned how to create and review pull requests.
* Steps practiced:

  * Pushed branch to GitHub
  * Opened a Pull Request
  * Added a description and assigned reviewers
* Notes: Understood workflow for collaboration and code review.

## **Day 6 — Merging & Resolving Conflicts**

* Topic: Learned how to merge branches and resolve merge conflicts.
* Commands practiced:

  ```bash
  git merge feature/test
  git merge main
  ```
* Notes: Learned how to handle conflict markers (`<<<<<< >>>>>>`).

## **Day 7 — GitHub Issues & Project Boards**

* Topic: Learned how to create issues and track tasks.
* Actions practiced:

  * Created issues for future learning tasks
  * Added labels and milestones
  * Used GitHub Projects (Kanban board)
* Notes: Helps organize and plan development work.
