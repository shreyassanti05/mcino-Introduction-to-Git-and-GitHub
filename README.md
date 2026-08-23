# 🔧 Git & GitHub Foundations

![Git](https://img.shields.io/badge/Version_Control-Git-F05032.svg)
![GitHub](https://img.shields.io/badge/Platform-GitHub-181717.svg)
![Automation](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF.svg)

## Overview
This repository serves as a practical implementation and demonstration of professional version control workflows using Git and GitHub. It showcases an understanding of collaborative software development, repository management, and basic CI/CD automation.

While foundational, mastering these workflows is critical for integrating into enterprise engineering teams and maintaining clean, traceable codebases.

---

## ⚡ Key Workflows Demonstrated
- **Branching Strategies:** Managing feature branches, resolving merge conflicts, and maintaining a clean `main` branch.
- **Pull Request Lifecycle:** Creating, reviewing, and merging Pull Requests with proper commit messaging.
- **Repository Automation:** Utilizing GitHub Actions to automate repository maintenance (e.g., auto-closing stale PRs).
- **Open Source Standards:** Implementing standard repository documentation including `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, and custom Issue Templates to standardize bug reports and feature requests.

---

## 🛠️ Tech Stack
- **Version Control:** Git (CLI)
- **Hosting & Collaboration:** GitHub
- **Automation:** GitHub Actions (YAML)
- **Scripting:** Python / Bash (Example scripts)

---

## 💡 Interview Talking Points

- **Why is a clean Git history important?**
  *A clean Git history is essential for debugging and team collaboration. I demonstrated the ability to use feature branches and write semantic commit messages so that if a bug is introduced in production, `git bisect` can easily identify the exact commit responsible.*

- **How do you handle GitHub Actions?**
  *I configured YAML-based GitHub Actions workflows in the `.github/workflows` directory. This proves my capability to move beyond basic Git usage and into DevOps and Continuous Integration, allowing the repository to automatically run scripts or manage pull requests based on specific trigger events.*

- **Why include a Code of Conduct and Contributing guide?**
  *Enterprise development requires standard operating procedures. By setting up Issue Templates and Contribution guidelines, I ensure that anyone contributing to the codebase provides the exact metadata needed (like reproduction steps for bugs), saving engineering time during triage.*
