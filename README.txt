These commands are for the Git Bash UI

1. 'git init' -> Powers your folder to be managed by git, and initialises a new empty
repository. It also creates a .git folder that has all the relevant logic to manage
versions of your project.

/* Running git init in an existing repository is safe. 
   It will not overwrite things that are already there. 
   The primary reason for rerunning git init is to pick up newly added templates. 
*/

2. 'Workubg Area -> there can be a bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet.
A file which is in working area is considered to be not in the staging area. When we do 'git status'
and we see a bunch of 'untracked files' then these are actually called to be in the working area.

3. 'Staging Area' -> What all files are going to be part of the next version that we will create.
This staging area is the place where git knows what changes will be done from the last version to
the next version.

4. 'Repository Area' -> This area actually contains the details of your all previous registered version.
and the files in this area, git already manages them and knows their version history.

5. 'git add <file>' -> moves the file from working area to staging area.

6. 'git rm --cached <file>' -> moves file back from staging area to working area.

7 'commit' -> Commit is aa particular version of th e project. It captures a snapshot of the project's staged
changes and created a version out of it.

8. 'git commit -m <message> -> registers staging changes to a commit

2. 'clear' ->  Clears the bash command line.

3. 'code .' -> Opens the VS Code in that directory.

4. 'touch new.txt' -> Create a new file new.txt.

5. 'ls' -> Shows the list of files in the directory.
6. 'ls -a' -> Shows all the files including hidden ones.

7. 'cd Folder' -> This is used to enter the Folder directory.
8. 'cd ..' -> Goes in previous directory.

9. 'mkdir A' -> This will create a folder names 'A'.

10. 'mkdir A B' -> This will create two folders names 'A' & 'B'.

11. 'mkdir 'New Folder' ' -> This will create a single folder named 'New Folder'.

12. echo 'Abhinav Singh' > new.txt -> This will save Abhinav Singh in new.txt.

13. 'rm -rf .git' -> Deletes the git repository(.git).

