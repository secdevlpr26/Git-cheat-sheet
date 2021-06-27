# Git-cheat-sheet

| Purpose  | Command |
| ------------- | ------------- |
| Initialise Git   | git init  |
| Configure user's username  | git config --global user.name “[username]”  |
| Configure user email  | git config --global user.email “used-email”  |
| Retrieve entire repo from remote  | git clone [url]  |
| Add file to a repo  | git add [file]  |
| Add all files   | git add . |
| Create a new file  | echo "# repo name" >> [file]  |
| Commit a change  | git commit -m "Commit Command"  |
| Check git status  | git status  |
| Show all commit history in the current branch  | git log  |
| Add remote url to an alias origin  | git remote add origin [url]  |
| Set different url to origin alias  | git remote set-url origin [url]  |
| Fetch all branches from git remote | git fetch [alias] |
| Check origin url  | git remote -v  |
| Check the available branches  | git branch -a  |
| Merge a branch's history to a current branch  | git merge [branch]  |
| Create new branch  | git branch [branchname]  |
| Show the commits of branchA not in branchB  | git log branchB...branchA  |
| Show commits that changed files across renames  | git log --follow [file]  |
| Show all commit logs with indication of any paths that moved  | git log --stat -M  |
| Switch to another branch and check it out in your directory  | git checkout  |
| Push local commit to exisitng repo  | git push -u origin master  |
| Push commits fast forwarded   | git push -f origin master  |
| Fetch and merge commits from tracking branch | git pull  |
| Uninstall git credentials  | git credential-manager uninstall  |
| Install git credentials  | git credential-manager install  |
| See what refs you have  | git show-ref  |
| Change the ref path  | git push origin HEAD:main  |
| Command line color  | git config --global color.ui auto  |
| Unstage a file while retaining changes in working directory  | git reset [file]  |
| Diff of what is changed but not staged  | git diff  |
| Diff of what is staged but not yet committed  | git diff --staged |
| Diff of what is in branchA that is not in branchB  | git diff branchB...branchA  |
| Show any object in Git in human readable format  | git show [SHA]  |
| Delete the file from project and stage removal for commit  | git rm [file]  |
| Change the existing file path and stage move  | git mv [existing-path] [new-path]  |
| Apply commit of current branch ahead of specified one | git rebase [branch] |
| Clear staging area, rewrite working tree from specified commit | git reset --hard [commit] |
| Save modified and staged changes | git stash |
| List stack-order of stashed file changes | git stashed list |
| Write working from top of stash stack | git stash pop |
| Discard the changes from top of stash stack | git stash drop |
