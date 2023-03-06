# Basic Git CLI Commands
This document will explain how to use basic Git CLI (Command Line Interface) commands.

## Clone a Repository
To clone a repository, use the git clone command followed by the URL of the repository.

```
git clone <repository URL>
```
For example, to clone a repository named "my-repo" hosted on GitHub, the command would be:

```
git clone https://github.com/username/my-repo.git
```

## Add and Commit Changes
To add changes to the staging area, use the git add command followed by the name of the file or directory you want to add.

```
git add <file or directory name>
```
To commit changes to the repository, use the git commit command followed by a message describing the changes.

```
git commit -m "Commit message"
```

## Push Changes
To push changes to the remote repository, use the git push command followed by the name of the remote repository and the branch you want to push to.

```
git push <remote repository name> <branch name>
```
For example, to push changes to the "main" branch of a remote repository named "origin", the command would be:

```
git push origin main
```

## Pull Changes
To pull changes from the remote repository, use the git pull command followed by the name of the remote repository and the branch you want to pull from.

```
git pull <remote repository name> <branch name>
```
For example, to pull changes from the "main" branch of a remote repository named "origin", the command would be:

```
git pull origin main
```
## View Repository Status
To view the status of the repository, use the git status command.

```
git status
```
View Commit History
To view the commit history of the repository, use the git log command.

```
git log
```
These are the basic Git CLI commands that will get you started with version control. As you become more familiar with Git, you can explore more advanced commands and workflows.