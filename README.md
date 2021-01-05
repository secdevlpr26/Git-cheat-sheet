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
| Check origin url  | git remote -v  |
| Check the available branches  | git branch -a  |
| Create new branch  | git branch [branchname]  |
| Push local commit to exisitng repo  | git push -u origin master  |
| Push commits fast forwarded   | git push -f origin master  |
| Fetch and merge commits from tracking branch | git pull  |
| Uninstall git credentials  | git credential-manager uninstall  |
| Install git credentials  | git credential-manager install  |
