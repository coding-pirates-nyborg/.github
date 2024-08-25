# Working with `git` and GitHub


- [Working with `git` and GitHub](#working-with-git-and-github)
  - [Cloning the Repository](#cloning-the-repository)
  - [Creating a Branch](#creating-a-branch)
  - [Committing Changes](#committing-changes)
  - [Pushing Changes](#pushing-changes)
  - [Creating a Pull Request](#creating-a-pull-request)
  - [Merging a Pull Request](#merging-a-pull-request)

---

> In all the examples below, replace `[your repository url here]` with the URL of the repository you want to clone. the angle brackets `[]` are not part of the URL, they are just there to indicate that you should replace the text inside them with your own text.

## Cloning the Repository

```bash

# Clone the repository  
git clone [YOUR_REPOSITORY_URL]

```

## Creating a Branch

```bash

# Create a new branch

git checkout -b [YOUR_BRANCH_NAME]

```

## Committing Changes

```bash

# Add all changes to the staging area

git add .

# Commit the changes

git commit -m "Your commit message here"

```

## Pushing Changes

```bash

# Push the changes to the remote repository

git push

```

## Creating a Pull Request

Use the github web interface to create a pull request.

1. Go to the repository on GitHub
2. Click on the `Pull Requests` tab
3. Click on the `New Pull Request` button
4. Select the branch you want to merge into
5. Click on the `Create Pull Request` button
6. Add a title and description for the pull request
7. Click on the `Create Pull Request` button

---

## Merging a Pull Request

Use the github web interface to merge a pull request.

1. Go to the repository on GitHub
2. Click on the `Pull Requests` tab
3. Click on the pull request you want to merge
4. Click on the `Merge Pull Request` button
5. Click on the `Confirm Merge` button
6. Delete the branch if you no longer need it

---
