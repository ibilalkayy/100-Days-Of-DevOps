In the first day, I have learned the following things about Git.

- `git init` will only track a particular directory in which git is initialized.
- `git status` will show the status of the files that are newly created, modified or deleted.
- `git add filename` OR `git add .` will add a particular or all the files into the staging area and it can now be tracked them before committing them into Git.
- `git commit -m "add a message"` will commit the changes in the git.
- `git commit -am "add a message"` will add the files into the staging area and commit it also.
- `git restore --staged filename` will move the files from the staging area to the unstaging area. In this way, the data will be reverted back.
- `git log` will show the history of all the git commits.
- `git reset hash value` will move the data from the committing area to the unstaging area. Provide the previous hash value if you want to delete the next one.
- `git stash` will store the data temporarily somewhere in the memory. The changes won't be committed. Instead it has to be added to the staging area and then it can go to the stashing area.
- `git stash push -m "add a message"` will store the data temporarily in the git stash.
- `git stash list` will show the list of data that are temporarily stored.
- `git stash clear` will delete the list of data that are present in the git stash.
- `git stash apply index number` will call the stashing in which you want to make changes.
- `git stash drop index number` will delete a specific data from the stashing list.
- `git stash pop index number` will transfer the specific index number data out of the stashing area so that it can be further committed. It means that the data is now able to be added into the staging area and committed also.
- `rm -rf .git` will unintialize the git. It means that all the branches will be deleted from Git.

## **Explaining it in a video**

You can find the video of it here. [1/100 Days DevOps Challenge]()