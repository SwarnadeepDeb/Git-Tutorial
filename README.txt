1. `git init` -> initialize the .git folder that has all the relevant logic to manage version of your project.
2. `rm -rf .git` -> It removes the .git folder from your project.
3.  `Working Area` -> In this area contains all the untrack files, If we do any changes to the file that are in working are these are not tracked by the git.
4. `Staging Area` -> This area contain all the files that are going to include in the next version.
5.  `git add <file>` -> This command will add the file from the working area to the staging area.
6. `git rm --cached <file>` -> this command is used to bring back the file from the staging area to the working area.
7. `Repository Area` -> This area contains the details of all your previous registered version. And the files in this area git already manages them and knows there version history.
8. `commit` -> Commit is a particular version of the project. It captures a snapshot fo the project's staged changes and creates a version out of it.
9. `git commit` -> registers staging changes to a commit.
10. `git log` -> List down all the commits of the reposatory.
11. `git restore <file>` -> It removes all the files changes from the staging area to be commited.
12. `git restore --staged <file>` -> It removes file changes from the staging area to the working area.