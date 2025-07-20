### git
```
# if u have a folder already set up for push, initialize the git first
git init
# then add 
git remote add origin <github repo link>
```

### branch
```
# create a branch
git checkout -b <branch name>
# or
git switch -c <branch name>

# switch to branch
git checkout <branch name>
# or
git switch <branch name>

# get back to master or main
git switch master
git checkout master

# if failed, add 'origin' before the brach name
git switch origin master
```

### updating the repo
```
# to pull all branch
git pull

# to pull only one branch
git pull origin master

# always do this before staging, committing, and pushing
```

### staging and commit
```
# adding all of the changed file to your plan-to-commit
git add .

# only add the necessary file
git add <file name.txt or path>

# confirm that the files have been added to staging
git status

# commit the staged files
git commit -m "<comment that describes the changes>"

# push all local changes
git push <remote> <branch name>
# ex: git push origin main
# or just
git push
```