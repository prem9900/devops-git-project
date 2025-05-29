
 📦 DevOps Git Project

Welcome to the **DevOps Git Workflow Project**! This project demonstrates how to manage version control using Git and GitHub by following professional best practices.



 📁 Project Structure

```
main                # Final production-ready code
└── Dev             # Active development branch
    └── feature/*   # Feature-specific branches (e.g., login page)
```



 🎯 Objective

To practice and understand how version control works in a real-world DevOps project using:
- Branching strategies
- Pull requests
- Commit messages
- Tags
- GitHub collaboration



## 🚀 Getting Started

 Clone the Repo
```bash
git clone https://github.com/prem9900/devops-git-project.git
cd devops-git-project
```



## 🔀 Branching Workflow

1. Create Development Branch
```bash
git checkout -b Dev
```

2. Create a Feature Branch from Dev
```bash
git checkout Dev
git checkout -b feature/your-feature-name
```

 3. Merge Feature to Dev (after work is done)
```bash
git checkout Dev
git merge feature/your-feature-name
```

4. Merge Dev to Main (final stage)
Use GitHub Pull Requests for merging.



📄 Key Files

- `index.html` – Sample file to start with
- `.gitignore` – File to exclude unnecessary files from Git
- `README.md` – This file, explaining the project
- Additional features/pages go into separate branches





✅ Outcome

By completing this project, you will understand:
- How to manage branches in Git
- Collaborative development using GitHub
- How to maintain a clean Git history



