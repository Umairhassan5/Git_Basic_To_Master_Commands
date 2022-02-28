**_Git Commands_**

**_Create simple text file or direcory_**

- mkdir test (Direcory)
- touch demo.txt

**Rename the file or direcotry**

- git mv demo.txt example.txt

**\*Delete the file**

- git rm example.txt

**_Check the status of the branch_**

- git status (The file changes will be shown in red before added)

**_Add the file to commit the changes_**

- git add "File Name" (Withoud quotes, after add it will be green)
  Note: (If you want to add the whole project files **_git add ._** )

**_Commit the changes_**

- git commit -m or am "New file added" ( To stage the changes , and also add the comment in double quotes)

**_Create New Branch_**

- git checkout -b "Branch Name"

**_Check the current branch_**

- git branch

**_Merge the branch with another branch_**

- git merge master (You should be in the current branch then run the command)
