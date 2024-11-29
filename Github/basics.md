GITHUB BASICS
==============

# WINDOWS

 ## Almost everything can be done by going to the search bar(Shift+CTRL+P) and type what you need

 ## Create repository
  - git init (or V)
  - Go to Source Control(CTRL+Shift+G)
  - Initialize Repository

 ## Add/Stage
  - Click the "+" signs in the files on SOURCE CONTROL
  - git add . (adds all the files)
  - git add -A (adds all the files, removes files from index that are no longer in the working tree)
  - git add -u(Update the index just where it already has an entry matching, but adds no new files and remove files deleted)
  - git add file
  - git add folder/*

 ## Commit
  - git commit -m "commit message"
  - Add a message on the box and click Commit

 ## Branches
  - Change name (git branch -m new_name)
  - New branch (git branch new_branch)
  - Move to a diffent branch (git checkout branch_name)
  - New branch and move to it (git checkout -b new_branch_name)
  - Merge branches, from the branch that you want the changes to be done (git merge new_feature)
  - Delete branch (git branch -d new_branch)

 ## Miscellaneous
  - Status (git status)