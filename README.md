Git Assignments 
=================
This assignment will review what we've learned on day 1 of git. To complete the assignment, you will need to get git set up, and perform some of the tasks that were taught in class. 

Configure git 
==============
Use the following commands to configure your identity on git. This makes sure your commits have the right name.
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com

Clone the assignment repository
================================
Clone down the assignment repository
$ https://github.com/SamTharani/Assignment-1-Git.git

Assignment
==========
Answer the questions in quiz.md. Answer each question in a separate commit. Follow the steps below for each commit.
•	Make changes to your files.
•	see if the file change is detected with git status.
•	see if the correct changes are detected with git diff.
•	stage the changes with git add <filename>.
•	check that the add did what you expected with git status.
•	check git diff again to make sure it no longer shows changes.
•	check git diff --cached to show the changes you have staged.
•	make the commit with git commit.
•	Write a meaningful commit message (e.g. "Answers question 1").
•	check that your working directory is clean with git status.
•	check that your commit succeeded as expected with git log (you should see your latest commit message on top).

Push your code up to a github repository.
Before you push up your code to your new repository, you will need to remove the reference to my repository with:
$ git remote rm origin

