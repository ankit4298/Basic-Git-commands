# BASIC GIT commands

### -------------------------------------------------------------
## Initial Setup Commands (one time)

## git config -l
#### This command is used to know all the configuration of machine where git is installed

## git config --global user.name "username"
#### To set the username

## git config --global user.email "ID@mail.com"
#### TO set the email

### -------------------------------------------------------------

### -------------------------------------------------------------
## Daily life commands

## git clone <url>
#### This command is used to clone the repository already created

## git status
#### This command is used to check the status of local repository, it checks if the files have any changes committed or not

## git add <filename / . / -A>
#### This command is used to add a new/updated file to be committed, "filename" can be given to add specific files or "." for adding all files or "-A" argument to add all files as well

## git commit -m "<message>"
#### This command is used to commit the files which are updated or newly created to be uploaded to remote repository, a message is necessary to know what the purpose of the update was, it can further be helpful to check in logs 

## git push
#### This command is used to add all the local files committed to remote repository

## git pull
#### This command is used to replace all the local repository files with the updated copy of files from the remote repository

## gitk <filename>
#### This command is used to check all the previous revisions on the file, the <message> from commit is used to track the name of the previous revisions name

### -------------------------------------------------------------