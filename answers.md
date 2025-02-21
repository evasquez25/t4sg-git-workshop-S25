1. What is the difference between git and GitHub?
 - git is a version control tool that works locally whereas GitHub is an online service
    used in conjuction with git to sync local code with an online copy of the same code.
2. Why is version control important?
 - Version control is important because it creates a history of changes made to a project.
    The bigger the project, the harder it is to keep track of changes, especially if those changes
    are made by different people in diffrent machines. Version control helps with keep all these
    changes organized and controlled.
3. What is the command to view a branch's commit history?
 - git log
4. What command lists all the branches in your local repository? Which one lists those in the remote?
 - git branch (for local)
 - git branch -r (for remote)
5. To prevent specific files and folders from being commited to a repository, what should you do?
 - You can use a .gitignore file to specify which files you don't want to add to your commits.
 - Alterantively, you can also just do git add (file names) for each file you do want to add,
    but this is extra lol.