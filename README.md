BRM Experiments  

Aim

To create, manage, and merge branches using Git and GitHub for organized and parallel code development. 

BRM Worksheet 1.2

Theory

A branch in Git represents an independent line of development within a repository. Branches allow developers to work on new features, bug fixes, or experiments without disturbing the main codebase.

Each Git repository typically contains:

One default branch (usually main)

Multiple feature or topic branches

Branching provides several advantages in software development:

Parallel Development: Multiple developers can work on different features simultaneously.

Safe Experimentation: Developers can test new ideas without affecting the main code.

Better Collaboration: Teams can review and integrate changes efficiently.

Clean Code Management: Different features and fixes are organized into separate branches.

Once development on a branch is completed, the changes can be merged into another branch using a Pull Request (PR) in GitHub. 

BRM Worksheet 1.2

Steps / Procedure
1. Creating a Branch Using GitHub (GUI Method)

Login to your GitHub account.

Open an existing repository.

Click on the branch dropdown (usually showing main).

Enter a new branch name (for example: feature1).

Click Create branch from main.

A new branch will be created from the default branch.

2. Creating a Branch Using Git (Command Line)

Open Git Bash / Terminal.

Navigate to your repository:

cd repository_name

Create a new branch:

git branch feature1

Switch to the new branch:

git checkout feature1

or

git switch feature1
3. Working on a Branch

Create or modify files in the new branch.

Check branch status:

git status

Add changes:

git add .

Commit changes:

git commit -m "Added feature in feature1 branch"
4. Push Branch to GitHub

Push the branch to GitHub using:

git push origin feature1

The branch will now be available on GitHub.

5. Creating a Pull Request

Go to the repository on GitHub.

Click Compare & pull request.

Select:

Base branch: main

Compare branch: feature1

Add a title and description.

Click Create Pull Request.

6. Merging a Branch

Review the pull request.

Click Merge pull request.

Confirm the merge.

The changes from the feature branch are now merged into the main branch.

7. Deleting a Branch

After successful merging:

Using GitHub

Click Delete Branch

Using Command Line

git branch -d feature1
Learning Outcomes

After completing this experiment, students will be able to:

Understand the purpose and importance of Git branches.

Create and switch between branches using Git.

Use feature branches for isolated development.

Merge branches using pull requests in GitHub.

Apply efficient branching strategies for collaborative development. 

BRM Worksheet 1.2