# Collaborative GitHub Workflow Demo

## 📌 Overview

This project demonstrates a **collaborative development workflow using GitHub**, focusing on proper team practices such as branching strategies, pull requests, code reviews, and issue tracking.

The application built is a **simple frontend-based Task Manager** with:

* Navbar (App name + Login/Signup)
* Login & Signup UI
* Todo list with localStorage support

---

## 🎯 Objectives

* Implement structured team collaboration using GitHub
* Enforce code quality using branch protection rules
* Use pull requests for controlled integration
* Assign reviewers and perform code reviews
* Track tasks using GitHub Issues

---

## 🏗️ Project Structure

```
collaborative-workflow-demo/
│
├── index.html
├── style.css
└── README.md
```

---

## 🌿 Branching Strategy

We followed an **industry-standard branching model**:

* `main` → Production-ready code (protected)
* `develop` → Integration branch
* `feature/*` → Individual feature development

### Flow:

```
feature branch → develop → main
```

---

## 🔒 Branch Protection Rules

### Applied to `main`:

* Require pull request before merging
* Require at least 1 approval
* Block direct pushes
* Require conversation resolution

### Applied to `develop`:

* Require pull request before merging
* Require at least 1 approval

### Purpose:

To ensure **code quality, review, and controlled integration**

---

## 🧩 Task Management using Issues

We created GitHub Issues to manage tasks:

1. #1 - Add Navbar UI
2. #2 - Add Login/Signup UI
3. #3 - Add Todo Logic using localStorage

Each issue represents a **feature or task assigned to a developer**

---

## 👥 Team Roles Simulation

We simulated a team using multiple accounts:

* **Account 1 (Owner)** → Maintains repository and merges PRs
* **Account 2 (Developer)** → Implements Login/Signup UI
* **Account 3 (Developer)** → Implements Todo Logic

---

## 🚀 Workflow Implementation

### 1. Issue Creation

Tasks were defined using GitHub Issues.

---

### 2. Feature Branch Creation

Each feature was developed in a separate branch:

* `feature/add-task-ui`
* `feature/login-ui`
* `feature/todo-logic`

---

### 3. Development Phase

Each developer:

* Worked independently on their feature
* Made changes locally using VS Code
* Committed and pushed changes to GitHub

---

### 4. Pull Request Creation

For each feature:

* A Pull Request (PR) was created
* Base branch → `develop`
* Feature branch → respective feature

Example:

```
feature/login-ui → develop
```

---

### 5. Code Review Process

* Reviewers were assigned to PRs
* Code was reviewed before merging
* Approval was required (branch protection enforced)

---

### 6. Merge Process

After approval:

* PR was merged into `develop`
* Feature branch optionally deleted

---

### 7. Final Integration

All features were integrated into the `develop` branch, forming the complete application.

---

## 🔄 Complete Workflow Summary

```
Issue → Feature Branch → Commit → Push → Pull Request → Review → Merge
```

---

## 💾 Local Storage Implementation

The application uses **localStorage** to simulate backend functionality:

* User data stored locally
* Current logged-in user tracked
* Tasks stored per user

### Example:

```
users → list of registered users
currentUser → active user
tasks_username → user-specific tasks
```

---

## ✅ Key Features Demonstrated

* Collaborative development
* Branching strategy
* Pull request workflow
* Code review mechanism
* Issue tracking
* Version control using Git

---

## 🎓 Learning Outcomes

* Understanding real-world GitHub workflows
* Importance of code reviews and approvals
* Managing multiple contributors
* Structuring projects using branches and issues

---

## 📢 Conclusion

This project successfully demonstrates a **collaborative GitHub workflow**, ensuring:

* Code quality
* Team coordination
* Organized development process

It reflects real-world software development practices used in industry environments.

