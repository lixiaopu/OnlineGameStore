# Git instruction

## Starting new task

Pull newest code from git. Create new branch from master branch. If required create from develop branch.

`git checkout master` or `git checkout develop`

`git status`

`git pull origin master` or `git pull origin develop`

Create new branch. Use task name from Trello.

`git checkout -b task-1`

And start your coding

## Pushing new code to git

Check you are in correct branch using `git brancus`

Run `git status` to check what files you have edited.

Add files you want to push to git:

`git add file1 file2` or  `git add .` if you want add all files.

Use `git status`, to check what files you have added.

You can use following `git diff --cached` to check you changes before commit.

When you are ready to push to git

`git commit -m "Task 1: put here relevant comment, that explain your changes. It dosen't matter if it is very long`

Then push you changes to git.

`git push origin task-1`


## Create Merge request
* Click 'new merge request'.
* Select source branch (your branch).
* Select taget branch, develop.
* Write tile for merge request 

"task-1 Changes I have made"
* Write more explixit description that tell changes you have made.
* Assign to someone you want to review you codes.
* Submit you merge request.

If merge request is assigned to you. 
Check changes that have been made.
Write comment, if required.
If everyting is ok, merge and delete old branch.

