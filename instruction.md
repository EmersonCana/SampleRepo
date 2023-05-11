#configure git

<!-- SETUP -->
<!-- setup name -->
git config --global user.name

<!-- setup email -->
git config --global user.email

<!-- setup default branch -->
git config --global init default branch main

<!-- git config help -->
git config -h

<!-- access the config documentation -->
git help config

#Initializing git
#Should access the work folder first

<!-- Initializing git -->
git init
<!-- Git will be initialized and will create a hidden folder named .git with the necessary git files -->

<!-- Check Repo Status -->
git status

<!-- Tracking a file -->
git add <filename>
<!-- alternatives -->
git add -all
git add -A
git add .

<!-- Remove file from tracking -->
git rm --cached <filename>

<!-- Ignore file from git -->
<!-- Create a .gitignore file -->
<!-- You can write the filename inside or * then extension -->

#Commit
<!-- Take snapshot of the repository at this time -->
git commit -m "message"



<!-- Show difference with the files -->
git diff

<!-- remove a file from staging -->
git restore --staged <filename>

<!-- Bypass staging -->
git commit -a -m "message"

<!-- Delete a file from git -->
git rm "filename"
<!-- Restore deleted file -->
git restore "filename"

<!-- Renaming a file -->
git mv "old_name" "new_name"

<!-- Review commits -->
git log 
git log --oneline
git log -p -> to exit press Q

<!-- amend - correct errors on commit -->
git commit -m "Updated message" --amend

<!-- Jump back to previous commit -->
git reset <commit_id>


#Branches
<!-- create branch -->
git branch <BranchName>

<!-- display branches -->
git branch

<!-- Switch branch -->
git switch <BranchName>

<!-- Merge changes -->
git merge -m "Message" <BranchName>

<!-- Delete a branch -->
git branch -d <BranchName>

<!-- Create and Switch to a new branch -->
git switch -c <BranchName>


<!-- Resolve Conflict -->

