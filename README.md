### SBA 1: Version Control

#### Description
This project is designed to challenge the ability to manage branches, handle merge conflicts, submit pull requests, and collaborate with others using GitHub.

#### Reflection on Branch Management, Merge Conflicts, and Pull Requests Creating and Managing Branches
##### Branch Management
 I followed a structured approach to branch management to ensure smooth development. First, I created a new branch from the main branch using the command git checkout -b feature/new-feature. This allowed me to work on my changes in isolation without affecting the main codebase. I made frequent, small commits with descriptive messages (git commit -m "Added a new branch") to track progress. Before pushing changes, I ensured my branch was up to date with main by running git pull origin main and resolving any discrepancies early.

##### Handling Merge Conflicts
During development, a merge conflict occurrs when another team member modifies the same file. In my case for this SBA, I created several branches from main (git checkout -b branch-name) and conflicts arose when I tried to merge all the branches with main. I opened the file in my editor, reviewed the differences, and manually merged the changes by keeping the necessary code from both branches. After resolving conflicts, I staged the file (git add index.html) and committed the merge (git commit -m "Resolve merge conflict in login feature"). This process reinforced the importance of frequent updates from the main branch to minimize conflicts.

##### The Pull Request Process
The pull request (PR) process was crucial for maintaining code quality and collaboration. Before submitting a PR, I reviewed my changes, ran tests, and ensured my branch was synced with main.

I followed the follwing steps to complete the pull request

- go to the Pull requests tab.

- Click "New pull request"

- On the Compare page:

  1. Compare branch: review/main

  2. base branch: main

- Click “Create pull request”

- Add a title and description, then click “Create pull request” again.

After reviewing the changes I merged the branches and deleted the review/main branch.

Overall, these practices helped maintain an organized workflow, reduce integration issues, and promote collaborative development.

#### Tools
- VScode
- git bash

#### Resources
I used class lectures and canvas materials to complete this task.
