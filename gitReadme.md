# Common
1. Status
```
git status
```
2. Clone
```
git clone <repo url>
```
3. Add for all just add a . at the end
```
git add <fileName> OR git add .
```
4. Commit
```
git commit -m <"some massage">
```
5. Push on Git Repo
```
git push origin <BranchName>
```
6. If You frequentaly push in same branch then use -u and next time just git push and done
```
git push -u origin <branchName>
git push    //for next time
```

# Branch 
1. List
```
git branch
```
2. Navigate
```
git checkout <nameofbranch>
```
3. Rename
```
git branch -M <NewName>
```
4. Create
```
git checkout -b <name>
```
5. Delete
```
git branch -d <NameOfBranch>
```
# Local Repo to Git Repo
1. Initialize Git Or add git folder
```
git init
```
2. Set origin
```
git remote add origin <https url>
```
3. Change existing Origin
```
git remote set-url origin <https url>
```
4. Verify Origin
```
git remote -v
```

# Basic
1. Show files
```
ls
```
2. All
```
-a
```
3. All name
```
.
```
4. Change Directory or For Back
```
cd <name>  or cd..
```
5. 

# Configure
1. Version Check
```
git --version
```
2. Set User Name
```
git config --global user.name <"name">
```
3. Set User Email
```
git config --global user.email <"email">
```