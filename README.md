# Git Demo Repository

Welcome to the Git Demo repository! This repository is designed for a hands-on demonstration of advanced Git concepts, providing a visual representation through HTML screens.

## Presentation Link

For a detailed presentation on the concepts demonstrated in this repository, please refer to the [Git Presentation]([<insert_link_here>](https://www.canva.com/design/DAF6F9_PXVM/KlQfvCc6jp6tFk0BayT0pA/view?utm_content=DAF6F9_PXVM&utm_campaign=designshare&utm_medium=link&utm_source=editor)).


## Table of Contents
- [Git Demo Repository](#git-demo-repository)
  - [Presentation Link](#presentation-link)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Repository Structure](#repository-structure)
  - [Branches](#branches)
    - [`main`](#main)
    - [`feature/merge-demo`](#featuremerge-demo)
      - [Incorporating Changes from `main` using Merge](#incorporating-changes-from-main-using-merge)
    - [`feature/rebase-demo`](#featurerebase-demo)
    - [Committer Name and Email Correction](#committer-name-and-email-correction)
  - [Demonstrations](#demonstrations)
    - [Interactive Rebase](#interactive-rebase)
    - [Cherry-pick](#cherry-pick)
    - [Merge vs. Rebase](#merge-vs-rebase)
  - [Getting Started](#getting-started)
  - [Contributing](#contributing)

## Introduction

This repository is created to help individuals understand and practice advanced Git concepts in a visual and interactive way. The demonstrations cover topics like interactive rebase, cherry-pick, and the differences between merge and rebase.

## Repository Structure

The repository is structured with HTML screens, commits, and branches to facilitate a step-by-step demonstration. The primary files include:
## Branches

### `main`

The `main` branch represents the primary development branch. It contains initial commits and serves as the starting point for feature branches.

### `feature/merge-demo`

The `feature/merge-demo` branch demonstrates the process of merging changes from the `main` branch. It was created from the `main` branch and contains its own set of commits. However, it needs to incorporate the latest changes from the `main` branch.

#### Incorporating Changes from `main` using Merge

To get the latest changes from `main` into this branch, use the following commands:

```bash
git checkout main
git pull origin main
git checkout feature/merge-demo
git merge main
```

### `feature/rebase-demo`
The `feature/rebase-demo` branch showcases the rebase process. Similar to feature/merge-demo, it was created from the main branch and has its own set of commits. It also needs to include the latest changes from the main branch.

Incorporating Changes from main using Rebase
To get the latest changes from main into this branch using rebase, follow these steps:

```bash
git checkout main
git pull origin main
git checkout feature/rebase-demo
git rebase main
```

### Committer Name and Email Correction
Some commits in the main branch have incorrect committer names and emails. To correct them, you can use the following commands:

```bash
git checkout main
git log  # Identify the incorrect commits
```
## Demonstrations

### Interactive Rebase

Demonstrates the process of interactive rebase, allowing users to visually understand how to rearrange commits and edit commit messages.

### Cherry-pick

Illustrates the cherry-pick process, showcasing how specific commits can be picked from one branch and applied to another.

### Merge vs. Rebase

Provides insights into the differences between merge and rebase, with practical examples highlighting their effects on commit history.

## Getting Started

To get started with this Git Demo, follow these steps:
1. Clone the repository to your local machine.
2. Explore the branches and review the commits to understand each demonstration.
3. Feel free to experiment with your own changes and observe the Git history.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or additional demonstrations, feel free to open an issue or submit a pull request.
