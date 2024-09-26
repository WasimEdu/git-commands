# Git Commands
#### Author:- Wasim
## This contains all the useful commands for Git 

Version control is a system that record changes in file or set of files over time so that you can recall specific versions later.

## Commands

Set global username and email for Git (Locally)
```sh
git config --global user.name "<your username>"
git config --global user.email "<your email>"
```

Show configuration
```sh
git config --list
```

Initialise an empty Git Repository
```sh
git int
```

Add remote origin URL
```sh
git remote add origin <your remote git url>
```

Show remote orgin URL
```sh
git remote -v
```

Remove remote origin URL
```sh
git remote remove origin
```


Clone an existing Git Repository
```sh
git clone <repository URL>
```

Add file/stage to git
```sh
git add <file name>
```

Add all files
```sh
git add .
```

Commit all the staged files to git
```sh
git commit -m "<your coommit message>"
```

Show the status of Git Repository
```sh
git status
```

Restore the files
```sh
git restore <file name>
```


Show branches of your Git Repository
```sh
git branch
```

Rename branch
```sh
git branch -M <your choosen branch name>
```


Create new branch
```sh
git branch -b <branch name>
```

Move to existing branch
```sh
git checkout <branch name>
git switch <branch name>
```

Remove a branch from Git
```sh
git branch -d <branch name>
```

Fetch all remote branches 
```sh
git fetch
```

Push your local changes to remote branch
```sh
git push origin <branch name>
```

Pull your remote changes to local 
```sh
git pull origin <branch name>
```

Check your git commits and logs
```sh
git log
```


