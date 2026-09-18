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

## Repository Structure

```text
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
├── README.md
└── hello.py
