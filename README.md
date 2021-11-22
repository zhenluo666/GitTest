# Git Tutorial
###  Basic Git commands
#### 1. Start with Git
##### --- Clone the repository to your local machine (go to the directory at your local machine)
git clone https://github.com/zhenluo666/GitTutorial
##### --- Instead of cloning, you can also creat a new repository at local machine (go to the directory at your local machine)
git init
#### 2. Get the status of repository at local
git status
#### 3. Include untracked files or update unstaged files at git status check (after you make changes to files in local repository)
##### --- Add/Update a specific file
git add filename
##### --- Add/Update all files within directory
git add *  
git add -A
#### 4. Discard changes to an existed file (restore the file wrt github server version)
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
#### 9. Edit git configuration file (author and email)
git config --global --edit
#### 10. Help
git --help
### Branches
#### 1. Make branches (avoid messing up with main/master branch and able to merge later)
git branch new_branch
git branch new_branch base_branch
git checkout -b new_branch
#### 2. Switch to a specific branch
git checkout branch_name
#### 3. Branch operation
git branch --list  
git branch -D branch_to_be_deleted  
git branch -M branch_to_be renamed  
git branch -C branch_to_be_copied





