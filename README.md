# Hello Class

In this tutorial, you’ll learn how to make a **Pull Request (PR)** on GitHub. A Pull Request is how you suggest changes to someone else’s repository. Think of it as saying: *“Here’s my homework, can you check it and maybe add it to the class project?”*

## Step 1: Fork the Repository
1. Go to this repo’s main page: [github-and-markdown-2](https://github.com/mjwagerman/github-and-markdown-2/).
2. In the top right corner, click the **Fork** button.  
   This makes your own copy of the repo under your GitHub account.


## Step 2: Clone Your Fork
1. On **your forked repo page**, click the green **Code** button.
2. Copy the URL (HTTPS is easiest).
3. Open your terminal and run:
   ```bash
   git clone <URL-you-copied>
   cd github-and-markdown-2
   ```
   
## Step 3: Make a New Branch
Always work on a new branch (not main):
   

   ```bash
   git checkout -b my-first-branch
   ```
## Step 4: Make Your Changes
Edit files in this repo (maybe add your name to a list, write a markdown note, or improve the tutorial).

Save your changes.

## Step 5: Stage and Commit
   ```bash
   git add .
   git commit -m "Added my first contribution"
   ```
## Step 6: Push to GitHub
Push your branch up to your fork:

   ```bash
   git push origin my-first-branch
   ```
## Step 7: Open a Pull Request
Go to your fork on GitHub.

You’ll see a prompt to “Compare & pull request.” Click it.

Write a short message about what you changed.

Click Create Pull Request.

## Summary
Fork → Clone → Branch → Edit → Commit → Push → PR
