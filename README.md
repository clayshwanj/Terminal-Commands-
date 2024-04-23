TERMINAL COMMANDS AND THEIR FUNCTIONS
mkdir <folder> - creating a directory.
cd <folder> - navigates the current location of the terminal to a specific folder.
git init - initializes the folder in which the terminal is currently in.
git remote add origin <https://....> - automatically creates a remote connection called origin.This in simple terms tells the remote repo(the one in the git hub account) to add the local repo(the one in the machine)
cd.. - used to go up one level of the directory tree.In most cases it navigates the terminal back to the desktop.(..refers to the directory immediately above the current directory "parent directory").
touch <file> - creating a new file.
git add <file> - adds the created file to the folder in which the terminal is currently in.
cd <file> - navigates to a particular file.
git add . - adds all types files(html,css,js,etc) to the folder.
git commit -m "message" - commits staged(added) changes with a message preventing the developer from writing a message in Vim editor,which is tough to exit but has an exiting short-cut(,+qEnter).
git push -u origin main - used when pushing commits for the first time in order to set upstream using the flag(-u/--set-upsteam)
git push - pushes commits if an upstream has already been set.
git branch <branch_name> - creates a new branch.
git checkout <branch_name> - switches terminal to the specified branch.
git branch -r - view all remote branches.
git branch -a - view all local and remote branches.
git status - gives information about the current location(desktop,folder,branch.etc) of the terminal.
ls - shows contents of the current working directory.
git pull upstream - allows developers to pull changes made or merged in the upstream in order to have the most recent updates.
git config --global init.defaultBranch main - set configuration values on a global level or local project level.
rm -rf - deleting files or directories.
git clone <https://....> - copies an existing git repository to the local machine.
git remote -v - views all links available (both orgin and upstream)
git remote add upstream <https://....> - adds an upstream link.
git mv <oldfile> <newfile> - changes the file name.(strictly takes 2 arguments)
