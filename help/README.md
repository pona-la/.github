# New to Github? We can help!

## I want to make a simple edit in one file

Github UI offers you a quick and easy way to do this!

1. Find the file you want to edit:

<img src="https://raw.githubusercontent.com/pona-la/.github/refs/heads/main/assets/github-help-01.png" />

2. Try to open Edit mode:

<img src="https://raw.githubusercontent.com/pona-la/.github/refs/heads/main/assets/github-help-06.png" />

3. Accept forking the repo:

<img src="https://raw.githubusercontent.com/pona-la/.github/refs/heads/main/assets/github-help-05.png" />

4. Make your changes.

5. Save your changes by committing them:

<img src="https://raw.githubusercontent.com/pona-la/.github/refs/heads/main/assets/github-help-03.png" />

6. Describe in the commit what you've edited:

<img src="https://raw.githubusercontent.com/pona-la/.github/refs/heads/main/assets/github-help-07.png" />

7. Open a pull request:

<img src="https://raw.githubusercontent.com/pona-la/.github/refs/heads/main/assets/github-help-08.png" />

We will receive a notification about the pull request, eventually review and merge it!

## I want to make lots of edits

At this point you should learn more about Git and Github.

**What is Git?** Git is a **version-control** program.
* **What is version control?** You likely know the simplest possible version control: undo-redo (Ctrl+Z, Ctrl+Y). Imagine undo-redo as a chain of past, present, and future file versions. If you undo and start typing, all your "redo" versions are lost, because the chain has to stay linear. But in **git** instead of a linear chain you have a tree - a branching structure. Thanks to this, no work is lost, and several people can work in parallel.
* A **commit** is each individual version in a tree.
* A **branch** is a part of the tree that is linear. We often have one main branch, and many small short-lived branches.
* Work done on one branch can be **merged** to another branch.
* A **repository**, or **repo** for short, is a folder that is version-controlled by Git.

**What is Github?** Github is online storage for repos. It's a lot like Google Drive, but for code.

With Github you have two copies of the repo: one on Github's computers (remote), one on your computer (local). Syncing between them is not automatic. You can **pull** new commits from the remote, and you can **push** new commits to the remote.

On Github there are user accounts, and they "own" files. To work together on the same files, you either need to have edit permissions, or you can **fork**: create a repo copy that you have edit permissions in. The original copy is called the **upstream**, and your fork is called the **downstream**.

When you want to help a project that you don't own, here's how what you usually need to do:
* **Fork** the repository.
* **Clone** your forked repository from Github to your computer.
* **Create a branch** for your feature.
* Do some work and **commit** it.
* **Push** the commit(s) to Github.
* Open a **pull request** - a request for the upstream owner to accept your work and **merge** it into their branch.

At that point you're done! Wait for the upstream maintainer to see and respond/accept your pull request.

## Need more details?

Further reading: https://www.freecodecamp.org/news/guide-to-git-github-for-beginners-and-experienced-devs/

Github Desktop: https://desktop.github.com/download/  
Github Desktop is a GUI for Git. It is an easy way to get started using Git on your computer.
