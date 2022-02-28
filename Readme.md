**Git Commands**

**Git Clone**

After creating new repository on git you can clone the repo with this command

- `git clone 'https://github.com/exampleRepo'`

**Create simple text file or direcory**

- `mkdir test` (Direcory)
- `touch readme.md` (File)

**Rename the file or direcotry**

- `git mv demo.txt example.txt`

**Delete the file**

- `git rm example.txt`

**Check the status of the branch**

- `git status` (The file changes will be shown in red before added)

**Add the file to commit the changes**

- `git add "File Name"` (Without quotes, after add it will be green)
  Note: (If you want to add the whole project files **git add .** )

**Commit the changes**

- `git commit -m or am "New file added"` ( To stage the changes , and also add the comment in double quotes)

**Create New Branch**

- `git checkout -b "Branch Name"`

**Delete the branch**

- `git branch -d "Branch Name"`

**Check the current branch**

- `git branch`

**Merge the branch with another branch**

- `git merge master`(You should be in the current branch then run the command)

**Create the tag**

- `git tag "Tag Name"`

**List of all tags**

- `git tag --list`

**Delete the tag**

- `git tag -d "Tag Name" or git tag -d` (To delete all tags)

**Logs of all commits**

- `git log` (Will show the all commits with comments)

**Stash the changes**

- `git stash list` ( Will show the all stash commits)
- `git stash` (All changes you done will be deleted or stashed)

**Stash changes revert**

- `git stash pop` (If you unintentially remove the changes it will revert the stash command)

**Reset the commit or go to previous commits `Soft && Hard`**

- `git log` (To check all commits)
- `git reset 'Commit' --soft` (This will not change the content of the file)
- `git reset --hard 'commit'` (This will totally change the content of the file which only exist in that commit)

**Check the origin before push**

- `git remote -v`

**Push the changes you have commited**

- `git push origin 'branch name'`

**Check changes you have done**

- `git diff` (This will only work before the changes has been staged means commited)

**Fetch the branch names created by other teamates**

- `git fetch -a`

**Pull from the branch**

- `git pull origin 'branch name'` (This command will update your project with different changes done by other teammates on same and from different branches)
