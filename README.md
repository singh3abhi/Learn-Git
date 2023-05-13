These commands are for the Git Bash UI

1. `git init` -> Powers your folder to be managed by git, and initialises a new empty
   repository. It also creates a .git folder that has all the relevant logic to manage
   versions of your project.

/_ Running git init in an existing repository is safe.
It will not overwrite things that are already there.
The primary reason for rerunning git init is to pick up newly added templates.
_/

2. `Workubg Area` -> there can be a bunch of files that are not currently handled by git.
   It means that changes done or to be done in those files are not managed by git yet.
   A file which is in working area is considered to be not in the staging area. When we do 'git status'
   and we see a bunch of 'untracked files' then these are actually called to be in the working area.

3. `Staging Area` -> What all files are going to be part of the next version that we will create.
   This staging area is the place where git knows what changes will be done from the last version to
   the next version.

4. `Repository Area` -> This area actually contains the details of your all previous registered version.
   and the files in this area, git already manages them and knows their version history.

5. `git add <file>` -> moves the file from working area to staging area.

6. `git rm --cached <file>` -> moves whole file back from staging area to working area.

7 `commit` -> Commit is aa particular version of th e project. It captures a snapshot of the project's staged
changes and created a version out of it.

8. `git commit -m <message>`-> registers staging changes to a commit

9. `git log` -> list downs all the commits of the repository. If you want to exit out of git log prompt
   press `q`.

10. `git restore <file>` -> it removes all files changes from the staging area to be committed. This can
    be useful, if we did some dirty piece of code and now no more want it. Instead of deleting every change
    line by line, we can restore it or you can say restore last clean version of the file.

11. `git restore --staged <file>` -> it removes file from changes from staging area to the working area.
    this only works if changes are in your staging area

12. Diff between git rm and git restore
    ans: if you want to move the whole file back to the untracked state, then we do git rm, otherwise if we
    just want the changes to be moved in working area or staging area then we git restore.

13. `git diff commit1 commit2` -> gives the difference of all file changes between two commits

14 `git commit -m "<your commit message>"` -> If we want to avoid opening a text editor like vim/nano to
add commit message we can use this following command

15. `git remote` -> list down all the remote connection names

16. `Remote connection` -> It helps you to link two git repositories for uploading and downloading changes
    from each otherwise

17. `git remote add <name of remote> <link of the remote>` : this command helps us to add a new link to the
    remote repo and give a name to it
    eg - 'git remote add origin https://github.com/singh3abhi/Learn-Git.git' here origin is just a name of remote

18. `git remote rm <name of remote>` : this command deletes a remote connection

19. `git remote rename <oldanme> <newname>` : this command remanes the remote connection

Note: The name of the remote connection is always used to establish communication between the repos

20. `git add <file1> <file2> <file3>`: this command will add multiple file changes together in the
    staging area

21. `git add .`: this command will add all files from working repo to staging area.

22. `git pull <remote name> <branch name>` : downloads latest changes from the branch of the mentioned remote in your local repo.

### Recommended practice to do

    - make changes
    - git add <file>
    - git commit
    - git pull
    - git push

23. Merge conflicts are a very common scnario

merge conflicts can occur if multiple people try to make changes to the same file, and then collaborate

3. `clear` -> Clears the bash command line.

4. `code .` -> Opens the VS Code in that directory.

5. `touch new.txt` -> Create a new file new.txt.

6. `ls` -> Shows the list of files in the directory.
7. `ls -a` -> Shows all the files including hidden ones.

8. `cd Folder` -> This is used to enter the Folder directory.
9. `cd ..`-> Goes in previous directory.

10. `mkdir A` -> This will create a folder names 'A'.

11. `mkdir A B` -> This will create two folders names 'A' & 'B'.

12. `mkdir 'New Folder` -> This will create a single folder named 'New Folder'.

13. `echo 'Abhinav Singh` > new.txt -> This will save Abhinav Singh in new.txt.

14. `rm -rf .git` -> Deletes the git repository(.git).
