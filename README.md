# CyberStorm
Here is where all of our codes for assignments and challenges will be posted

# Git Setup

1. Get git bash [here](https://git-scm.com/download/win)
2. Copy this [link](https://github.com/QueenShorty/CyberStorm.git)
3. Open git bash - It should open once finished installing 
4. Nagivate to desired locaiton using git bash
    a. Use command cd "file name"
    b. If unsure where you are you can use dir command
5. Run command: git clone https://github.com/QueenShorty/CyberStorm.git
6. This command pulls the most updated code down into the file you selected, naming it CyberStorm. 

## Git Commands

### git pull
Pulls all the updated code and including new branches 
### git push
To push all your new changes
### git status
Allows you to see which files have changes, need to be committed
### git add .
Adds all files with changes to stagging - make sure to check the status so you're not commiting files you don't need to
### git commit -m "message"
Permanently stores your changes from staging to the repository
### git checkout "branch name"
Allows you to checkout a branch to work in
### git branch "new_branch_name"
Commands creates a new branch. Make sure to be in master before running this command
### git branch 
Tells you which branch you're on
### git merge "branch_name"
Merges branch_name into current branch. always merge master branch into current branch before pusing to new branch to master
### git push --set-upstream "name" master
When you create a new branch you need to push to origin

## Branch Structure
I have created a branch called WorkingInProgress - this is where we will be working on all our assignments and challenges. 

Once our assignments/challenges have been completed and working, we will merge changes into master

There also will be a branch for each person on the team - these branches are only for that user to push their individual assignments too.

## File Structure
In side of WorkingInProgess will be two folders - Assignments and Challenges. 

Option - we can also create a folder for the files or task 

In your own branch you may create your folders how you like.

## Naming Conventions
Inside of Assignments and Challenges folder which are located in Branch WorkingInProgess, each file will be named with the title of the homework or documents needed to complete the homework/assignments
