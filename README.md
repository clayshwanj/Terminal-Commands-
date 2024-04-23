#TERMINAL COMMANDS AND THEIR FUNCTIONS
1.mkdir <folder> - creating a directory.
2.cd <folder> - navigates the current location of the terminal to a specific folder.
3.git init - initializes the folder in which the terminal is currently in.
4.git remote add origin <https://....> - automatically creates a remote connection called origin.This in simple terms tells the remote repo(the one in the git hub account) to add the local repo(the one in the machine)
5.cd.. - used to go up one level of the directory tree.In most cases it navigates the terminal back to the desktop.(..refers to the directory immediately above the current directory "parent directory").
6.touch <file> - creating a new file.
7.git add <file> - adds the created file to the folder in which the terminal is currently in.
8.cd <file> - navigates to a particular file.
9.git add . - adds all types files(html,css,js,etc) to the folder.
10.git commit -m "message" - commits staged(added) changes with a message preventing the developer from writing a message in Vim editor,which is tough to exit but has an exiting short-cut(,+ q +Enter).
11.git push -u origin main - used when pushing commits for the first time in order to set upstream using the flag(-u/--set-upsteam)
12.git push - pushes commits if an upstream has already been set.
13.git branch <branch_name> - creates a new branch.
14.git checkout <branch_name> - switches terminal to the specified branch.16.git branch -r - view all remote branches.
15.git branch -a - view all local and remote branches.
16.git status - gives information about the current location(desktop,folder,branch.etc) of the terminal.
17.ls - shows contents of the current working directory.
18.git pull upstream - allows developers to pull changes made or merged in the upstream in order to have the most recent updates.
19.git config --global init.defaultBranch main - set configuration values on a global level or local project level.
20.rm -rf - deleting files or directories.
21.git clone <https://....> - copies an existing git repository to the local machine.
22.git remote -v - views all links available (both orgin and upstream)
23.git remote add upstream <https://....> - adds an upstream link.
24.git mv <oldfile> <newfile> - changes the file name.(strictly takes 2 arguments)
