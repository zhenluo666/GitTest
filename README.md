# Git Tutorial
### Git commands
#### 1. Clone the repository to your local machine (go to the directory at your local machine)
git clone https://github.com/zhenluo666/GitTutorial
##### --- Instead of cloning, you can also creat a new repository at local machine (go to the directory at your local machine)
git init
#### 2. Get the status of repository at local
git status
#### 3. Include untracked files or update unstaged files at git status check
##### --- Add/Update a specific file
git add filename
##### --- Add/Update all files within directory
git add *  
git add -A
#### 4. Discard changes to an existed file
git restore filename
#### 5. Commit the change (with messages -m)
git commit -m "updated the README with more commands"
#### 6. Sync the repository from local to github server
git push
#### 7. Sync the repository from github server to local
git pull
#### 8. Editing in git config (save or exit)
##### --- Press Esc to change from Edit Mode to Command Mode.  
##### --- Exit only
:q
##### --- Exit without saving
:q!
##### --- Exit with saving
:wq
