# Git Basics
Here are the basic commands you will need to use Git. See https://git-scm.com/docs for full information.

* `git status` Get the Git status of the files under control in the current directory.
* `git config --global user.name <name>` Set your name (used by commits). 
* `git config --global user.email <email>` Set your email (used by commits).
* `git config --global core.editor "atom --wait"` Configure Atom to be your Git commit editor.
* `git config --list` Check your settings.
* `git init` Initialize a Git repository.
* `git clone <url>` Clone and download a repo.
* `git add <file>` Start tracking new file(s).
* `git commit <file>` Commit changes to the repo. 
* `git commit -a` Use the `-a` switch with the commit command to automatically "add" changes from all known files (i.e. all files that are already listed in the index) and to automatically `rm` files in the index that have been removed from the working tree, and then perform the actual commit. Use the `-m "<message>"` switch to enter a `<message>` to be recorded against the changed files.
* `git push` Push changes

To switch remote URLs:
* `git remote -v` List your existing remotes in order to get the name of the remote you want to change.
* `git remote set-url origin <new URL>` Change your remote's URL from current one to <new URL>.
* `git remote -v` Verify that the remote URL has changed.