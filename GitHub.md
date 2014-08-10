# Starting with Git and GitHub

* Open https://github.com and create yourself an account!

* to install git on linux just type:
```
$ sudo apt-get intall git
```
* Next you have to set up your git, just follow the setup manual here - https://help.github.com/articles/set-up-git

* Now you need to create SSH key, for that jsut follow the instructions here - https://help.github.com/articles/generating-ssh-keys

* Create your first repository on GitHub, and a new folder for your project on your computer

# Git Commands

## Initiating Git repo
Go to the folred you have created now:

* ```$ git init``` - tells that this folder is a Git repository

* ```$ git remote add <name_of_remote> <url_to_remote>``` - connects this folder to your Git repository

Here is an example:

* ```$ git remote add origin git@github.com:YourGit/TestGit.git```

* ```$ git remote -v``` - checks if the folder is connected to the Git repository, if everything is fine you will see this:
```
origin  git@github.com:YourGitName/FolderName.git (fetch)
origin  git@github.com:YourGitName/FolderName.git (push)
```

* ```$ git push -u origin master``` - this commands takes your files and puts them into your Git repository. You are going to use it once, only for your first commit of new repository.
```git push <name_of_remote> <name_of_branch>``` - this command is what you are going to use for every other push to GitHub

* ```$ git pull origin master``` - gets files from repository

## Git add commands
* ```$ git add .``` - stages new + modified files in directory

* ```$ git add -u ``` - stages modified + deleted files

* ```$ git add -A``` - does both above

* ```$ git rm <filename>``` - to remove files from the working tree and the index, again before using the commit command;\

## Git commit commands

* ```$ git commit -m 'msg about what new in this commit'``` - record changes to the repository

## Git Branch commands

To create new branch type:
* ```$ git checkout -b branch-name```

To check for branches:
* ```$ git branch```

To switch to another branch:
* ```$ git checkout branch-name```

To push updated files:
* ```$ git push origin branch-name```
