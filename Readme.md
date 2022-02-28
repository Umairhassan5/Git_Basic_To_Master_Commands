**Git Commands**

**Create simple text file or direcory**

- mkdir test (Direcory)
- touch demo.txt

**Rename the file or direcotry**

- git mv demo.txt example.txt

**Delete the file**

- git rm example.txt

**Check the status of the branch**

- git status (The file changes will be shown in red before added)

**Add the file to commit the changes**

- git add "File Name" (Without quotes, after add it will be green)
  Note: (If you want to add the whole project files **git add .** )

**Commit the changes**

- git commit -m or am "New file added" ( To stage the changes , and also add the comment in double quotes)

**Create New Branch**

- git checkout -b "Branch Name"

**Delete the branch**

- git branch -d "Branch Name"

**Check the current branch**

- git branch

**Merge the branch with another branch**

- git merge master (You should be in the current branch then run the command)
