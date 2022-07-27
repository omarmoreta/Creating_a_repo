# Creating_a_repo

How to create a remote repository(repo) on github, create a local project, and pushing local repo to remote repo.

1. Create repo on github. Read github docs if you need some help.

2. Navigate to where you want to create and save your project on you local machine using the terminal.
```
cd Desktop
mkdir new_project_name
cd new_project_name
touch index.html style.css scripts.js
```

3. Initialize git inside local repo, add, and commit local changes using the terminal.
```
git init
git add -A  
git commit -m "initializing git and creating html, css, js files"
```
These can also be used for staging changes: 
```
git add .
```
stages all changes
or
```
git add index.html style.css scripts.js
```
stages changes in individual files.

4. Give your local repo a url reference to the remote repo on github and push upstream to it.
```
git remote add origin https://github.com/omarmoreta/Creating_a_repo.git
git push -u origin main
```
