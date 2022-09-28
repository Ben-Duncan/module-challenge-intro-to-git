## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?

Git is a program that multiple coders can use to collaborate their
projects on. A version control system.

2. What is the difference between Git and GitHub?

Git is used for writing code, GitHub is used to store, pull, and push
code files.

3. Why do we create a branch?

Branches are used to safely write code apart from the main branch.
These may be used to fix bugs amongst other things.

4. What is the purpose of a Pull Request?

Pull requests allow branches that someone worked on to be 
collaborated upon by other users, prior to merging to a main
branch.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.

git checkout 'branch name'

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

git fetch- used to determine changes in the remote repository. This does not affect the local repository.
git merge- combines branches into a single branch, used when other branches have been worked on.
git pull- takes the remote repository and commits changes into the local repository.

7. What is a merge conflict?

an error when merging branches, that git needs manual help to resolve the final product. 

8. How do you resolve a merge conflict?

Opening and editing the conflicted file. Git reset and git merge --abort can be useful in returning to the state prior to the merge. GitHub also has some tips on how
to resolve a merge conflict.
