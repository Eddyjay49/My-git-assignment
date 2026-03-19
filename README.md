# My Git Assignment

Getting used to version control

---

## What is Version Control?

Version control is a system that helps developers track changes made to code over time.  
It allows you to go back to previous versions if something goes wrong and also helps teams work together on the same project without conflicts.

---

## Difference Between Git and GitHub

- **Git** is a tool used to track changes in your code locally on your computer.
- **GitHub** is a platform used to store your Git repositories online and collaborate with others.

---

## Alternatives to GitHub

1. GitLab
2. Bitbucket
3. SourceForge

---

## Difference Between Git Fetch and Git Pull

- **Git Fetch**: Downloads changes from the remote repository but does NOT merge them into your current branch.
- **Git Pull**: Downloads changes AND automatically merges them into your current branch.

---

## What is Git Rebase?

Git rebase is used to move your branch to the latest version of another branch.

### Command:

```bash
git rebase main

```

## What is Git Cherry-pick?

git cherry-pick allows you to select a specific commit from another branch and apply it to your current branch

### Command:

```bash
git cherry-pick <commit-hash>
```
