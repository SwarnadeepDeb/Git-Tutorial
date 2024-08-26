1. `git init` -> initialize the .git folder that has all the relevant logic to manage version of your project.
2. `rm -rf .git` -> It removes the .git folder from your project.
3.  `Working Area` -> In this area contains all the untrack files, If we do any changes to the file that are in working are these are not tracked by the git.
4. **Staging Area** -> This area contain all the files that are going to include in the next version.
5.  `git add <file>` -> This command will add the file from the working area to the staging area.
6. `git rm --cached <file>` -> this command is used to bring back the file from the staging area to the working area.
7. **Repository Area** -> This area contains the details of all your previous registered version. And the files in this area git already manages them and knows there version history.
8. **commit** -> Commit is a particular version of the project. It captures a snapshot fo the project's staged changes and creates a version out of it.
9. `git commit -m "commit message"` -> registers staging changes to a commit.
10. `git log` -> List down all the commits of the reposatory.
11. `git restore <file>` -> It removes all the files changes from the staging area to be commited.
12. `git restore --staged <file>` -> It removes file changes from the staging area to the working area.
13. **Diff between git remove and git restore**
Ans:- If we want to remove whole file to the untracked state, then do git rm, otherwise if we
just want to the changes to be moved in working area or staging area then we do git restore.
14. `git diff commit1 commit2` -> gives the difference of all the file changes between two file commits.
15. `git remote` -> List down all the remote connections name.
16. Remote connections -> It helps you to link two git repositories for uploading and downloading changes from each other.
17. `git remote add <name of the remote> <link of the remote>` -> This command helps us to add a new link to the remote repo and give a name to it.
18. `git remote rm <name of the remote>` -> This command deletes a remote connection.
19. `git remote rename <oldname> <newname>` -> This command renames the remote connection.

**Note**:- The name of the remote connection is always used to establish communication between the repos.
