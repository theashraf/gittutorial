# Git Tutorial

### steps to initial commit
```sh
git init
git remote add origin https://github/username/reponame.git
git add .
git commit -m "CommitMsg"
```

### steps to develop a new feature
```sh
#create a new branch 
git branch featurename
git checkout featurename
#make some changes
git add .
git commit -m "Commiting Feature #2"
#pushing the branch to the remote repo
git push -u origin featurename
```
