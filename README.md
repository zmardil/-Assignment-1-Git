Git Assignments 
=================
This assignment will review what we've learned on day 1 of git. To complete the assignment, you will need to get git set up, and perform some of the tasks that were taught in class. 

Configure git 
==============
Use the following commands to configure your identity on git. This makes sure your commits have the right name.
<i>$ git config --global user.name "John Doe"<br>
$ git config --global user.email johndoe@example.com</i>

Clone the assignment repository
================================
Clone down the assignment repository
<i>$ https://github.com/SamTharani/Assignment-1-Git.git</i>

Assignment
==========
Answer the questions in quiz.md. Answer each question in a separate commit. Follow the steps below for each commit.
1.Make changes to your files.<br>
2.see if the file change is detected with git status.<br>
3.see if the correct changes are detected with git diff.<br>
4.stage the changes with git add <filename>.<br>
5.check that the add did what you expected with git status.<br>
6.check git diff again to make sure it no longer shows changes.<br>
7.check git diff --cached to show the changes you have staged.<br>
8.make the commit with git commit.<br>
9.Write a meaningful commit message (e.g. "Answers question 1").<br>
10.check that your working directory is clean with git status.<br>
11.check that your commit succeeded as expected with git log (you should see your latest commit message on top).<br>

Push your code up to a github repository.<br>
Before you push up your code to your new repository, you will need to remove the reference to my repository with:<br>
<i>$ git remote rm origin</i>

