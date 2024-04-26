# TERMINAL COMMANDS AND THEIR FUNCTIONS

# Open in the code editor to get a better view of the document.

1. mkdir <folder> - creating a directory.
2. cd <folder> - navigates the current location of the terminal to a specific folder.
3. git init - initializes the folder in which the terminal is currently in.
4. git remote add origin <https://....> - automatically creates a remote connection called origin.This in simple terms tells the remote repo(the one in the git hub account) to add the local repo(the one in the machine)
5. cd.. - used to go up one level of the directory tree.In most cases it navigates the terminal back to the desktop.(..refers to the directory immediately above the current directory "parent directory").
6. touch <file> - creating a new file.
7. git add <file> - adds the created file to the folder in which the terminal is currently in.
8. cd <file> - navigates to a particular file.
9. git add . - stages all types files(html,css,js,etc) to the folder.
10. git commit -m "message" - commits staged(added) changes with a message preventing the developer from writing a message in Vim editor,which is tough to exit but has an exiting short-cut(, + q +Enter).
11. git push -u origin main - used when pushing commits for the first time in order to set upstream using the flag(-u/--set-upsteam)
12. git push - pushes commits if an upstream has already been set.
13. git branch <branch_name> - creates a new branch.
14. git checkout <branch_name> - switches terminal to the specified branch.16.git branch -r - view all remote branches.
15. git branch -a - view all local and remote branches.
16. git status - gives information about the current location(desktop,folder,branch.etc) of the terminal.
17. ls - shows contents of the current working directory.
18. git pull upstream - allows developers to pull changes made or merged in the upstream in order to have the most recent updates.
19. git config --global init.defaultBranch main - set configuration values on a global level or local project level.
20. rm -rf <folder> - deleting a directory and all its files.
21. git clone <https://....> - copies an existing git repository to the local machine.
22. git remote -v - views all links available (both orgin and upstream)
23. git remote add upstream <https://....> - adds an upstream link.
24. mv <oldfile> <newfile> - changes the file name.(strictly takes 2 arguments)
25. git rm --cached <file> - delete the file from the version control system(git), but still, it can be tracked in the repository. It also can be re-added on the version control system.
26. git reset --hard - In addition to unstaging changes, the --hard flag tells Git to overwrite all changes in the working directory, too. Be sure you want to throw away your local developments before using it.
27. git --version - check the git version.
28. git config --global user.email '...@gmail.com' / name'Name..' - add email and name respectively.
29. git pull upstream main - pulls the most recent commits from the main branch of the upstream to the local repo
30. git push - pushes the pulled changes from the local repo to the remote repo.
31. git pull origin main - updates the local repo(in the pc) with changes merged in the remote repo(in the git hub accont).
