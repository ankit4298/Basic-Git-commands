# BASIC GIT commands

### -------------------------------------------------------------

## :arrow_forward: Initial Setup Commands (one time)

### _git config -l_
#### This command is used to know all the configuration of machine where git is installed

### _git config --global user.name "username"_
#### To set the username

### _git config --global user.email "email"_
#### TO set the email

### -------------------------------------------------------------

## :arrow_forward: Daily life commands

### _git clone <url>_
#### This command is used to clone the repository already created

### _git status_
#### This command is used to check the status of local repository, it checks if the files have any changes committed or not

### _git add <filename / . / -A>_
#### This command is used to add a new/updated file to be committed, "filename" can be given to add specific files or "." for adding all files or "-A" argument to add all files as well

### _git commit -m "\<message\>"_
#### This command is used to commit the files which are updated or newly created to be uploaded to remote repository, a message is necessary to know what the purpose of the update was, it can further be helpful to check in logs 

### _git push_
#### This command is used to add all the local files committed to remote repository

### _git pull_
#### This command is used to replace all the local repository files with the updated copy of files from the remote repository

### _gitk <filename>_
#### This command is used to check all the previous revisions on the file, the <message> from commit is used to track the name of the previous revisions name

### _git mv old_filename new_filename
#### It is used to rename file

### -------------------------------------------------------------