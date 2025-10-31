# teamup-lms
Exploring GitHub project management -----from issues to done 
# Achine GitHub Projects Demo

## 📘 Overview
This repository is created for learning and practicing **GitHub Issues**, **Project Boards**, and **workflow automation**.

It demonstrates how to:
- Create and manage issues effectively  
- Organize tasks using project boards  
- Link commits, pull requests, and issues  
- Automate issue closure through PRs  

---

## 🧩 Features
- 🗂️ GitHub Issues with labels and milestones  
- 🚀 Project Board (To Do → In Progress → Done)  
- 🔗 Branches and commits linked to issues  
- 🤝 Pull requests with automatic issue closure  

---

## 🧠 Learning Goals
By completing this project, you’ll understand how to:
1. Write structured and meaningful issues  
2. Use labels, assignees, and projects  
3. Create branches for specific issues  
4. Link PRs and automate task tracking  

---

## ⚙️ Tools Used
- **GitHub Issues** – for task tracking  
- **GitHub Projects (Board view)** – for progress visualization  
- **Git & CLI** – for version control and branching  
- **VS Code / Any IDE** – for making code changes  

---

## 🚀 Workflow Example

1. Create an issue  
2. Add it to the project board  
3. Create a branch for that issue  
4. Commit and push changes referencing the issue number  
5. Open a pull request  
6. Merge PR to close the issue automatically  

---

## 📄 Example Commands

```bash
# Create a new branch for your issue
git checkout -b fix/login-validation-#1

# Stage and commit changes
git add .
git commit -m "fix: improve login validation (#1)"

# Push to GitHub
git push origin fix/login-validation-#1
