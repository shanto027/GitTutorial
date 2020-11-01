# GitTutorial for all time

[Git tutorial](https://github.com/shanto027/GitTutorial) provides basic and advanced concepts of Git and GitHub. Our Git tutorial is designed for beginners and professionals.

![screenshots of example app](/images/screenshots@2x.png)


### The Git config command

This command sets the author name and email address to be used with your commits.

```
git config --global user.name "User name" 

git config --global user.email  "Email address"   

```


To create a blank repository, open command line on your desired directory and run the init command as follows:

```
git init Test

```

To add files to the repository, run the git add command as follows:

```
git add Filename  

```

We can list all the untracked files by git status command.

```
git status  

```

This command is used to make a copy of a repository from an existing URL. If I want a local copy of my repository from GitHub, this command allows creating a local copy of that repository on your local directory from the repository URL.

```
git clone URL 

```

This command changes the head. It records or snapshots the file permanently in the version history with a message.


```
git commit -m " Commit Message"  

```

This command lists all the branches available in the repository.

```
git branch  

```

This command is used to merge the specified branch?s history into the current branch.

```
git merge BranchName 

```

This command pushes all the branches to the server repository.

```
git push --all  

```


Pull command is used to receive data from GitHub. It fetches and merges changes on the remote server to your working directory.

```
git pull URL  

```

This command is used to check the commit history.
```
git log 

```