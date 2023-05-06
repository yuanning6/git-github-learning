# Learn Git & Github

Learn git from scratch.

## Subheader

clone remote repo


`git add .` add all files, include untracked files.

`git add index.html` add individual file or folder.

`git commit -m "message" -m "description"` commit with message and description.

**Short cut** `git commit -am "message"` add and commit at the same time, only works for modified files.

`git push origin main` push to repo main branch.

## Branch

`git branch` check current branches.

`git checkout -b [new branch name]` create a new branch and switch to it.

`git checkout [branch name]` switch to another branch.


## Merge

`git diff [branch name]` see differences between the [branch] and main branch.

`git push --set-upstream origin [branch name]` or `git push --u origin [branch name]` push to repo in a new branch.

After merging,

`git pull origin main` pull changes to local.

`git branch -d [branch name]` delete the branch.

## Undo

`git reset` undo last add.

`git reset HEAD` `git reset HEAD~1` undo last commit.

`git reset [commit hash]` unstage changes after reset.

`git reset --hard [commit hash]` not just unstage, completely remove changes after reset.

`git log` see all commits.