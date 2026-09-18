# Git & GitHub Workflow Practice

A hands-on repository for learning and practicing professional Git and GitHub workflows used in software development.

## Overview

This repository documents practical Git and GitHub exercises completed while learning version control, repository management, branching, collaboration, and remote synchronization.

The goal is to build a strong foundation for working with Git-based development workflows before moving into larger Python, REST API, backend, and AI automation projects.

## Technologies

- Git
- GitHub
- Python
- Markdown

## Git Concepts Practiced

### Repository Management

- `git init`
- `git status`
- `git log`
- `git log --oneline`
- `git diff`

### Staging & Commits

- `git add`
- `git commit`
- Meaningful commit messages
- Reviewing commit history

### Remote Repository Management

- `git remote`
- `git remote -v`
- `git push`
- `git pull`
- `git clone`

### Branching

- Creating branches
- Renaming branches
- Switching branches
- Working with feature branches
- Merging branches

### Collaboration Workflow

- Feature branch workflow
- GitHub Pull Requests
- Pull Request merging
- Remote branch synchronization

### Merge Conflicts

- Creating a merge conflict
- Identifying conflict markers
- Resolving conflicts
- Staging the resolved file
- Completing the merge

### Repository Security & Organization

- `.gitignore`
- Excluding unnecessary files
- Keeping repositories organized
- Avoiding sensitive information in repositories

git-github-workflow-practice/
│

Example Workflow

A basic Git workflow practiced in this repository:

Working Directory
        ↓
    git add
        ↓
Staging Area
        ↓
   git commit
        ↓
 Local Repository
        ↓
    git push
        ↓
     GitHub
For collaboration:
master
   │
   ├── feature branch
   │       │
   │       ├── changes
   │       └── commits
   │
   └── Pull Request
           ↓
        Review
           ↓
         Merge
├── .gitignore

Key Commands
# Initialize repository
git init

# Check repository status
git status

# Stage changes
git add .

# Commit changes
git commit -m "Meaningful commit message"

# View commit history
git log --oneline

# Create a branch
git switch -c feature/example

# Switch branches
git switch master

# Merge a branch
git merge feature/example

# Clone a repository
git clone <repository-url>

# Pull remote changes
git pull

# Push local commits
git push
What I Learned

Through this practice repository, I worked with:

Git repository initialization
Working directory, staging area, and repository
Commits and commit history
Remote repositories
GitHub repository management
Branch creation and switching
Feature branches
Pull Requests
Branch merging
Merge conflict resolution
.gitignore
Local and remote synchronization
Purpose

This repository serves as a practical Git/GitHub learning project and reference for future software development work.

The Git workflow practiced here will be used in larger projects involving:

Python
REST APIs
FastAPI
PostgreSQL
Backend development
AI automation
LLM applications
Author

Iman Fatima

GitHub:
https://github.com/imanfatima-analytics


### Also fix the repository's **About** section

Your current repository has **no description or topics**. :contentReference[oaicite:2]{index=2}

Use:

**Description**
```text
Hands-on Git and GitHub workflow practice covering version control, branching, Pull Requests, merging, conflict resolution, and remote repository management.

Topics

git
github
version-control
git-workflow
branching
pull-requests
merge-conflicts
software-development

This makes the repository immediately understandable when someone visits it. GitHub specifically recommends clear repository information and useful READMEs for people reviewing your work.

Then commit it

From your repository folder:

git add README.md
git commit -m "Create professional GitHub workflow README"
git push origin master
├── README.md
└── hello.py

## Repository Structure

