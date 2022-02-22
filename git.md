# Git Reference


Pushing inital commit to github

Go to the project directory

First add gitignore file

```
code .gitignore
```
The above is using vs code, and save the file

```
git init
```
then

```
git add .
```

then 

```
git commit -m "initial commit"
```
Create a repository in Githun
Pulish the branch to Github
```
git remote add origin <github_repo_url>
```
Then push to the branch
```
git push -u origin main
```

To determine the details of the current local repo's remote details 
 ```
 git remote show origin 
 ```
 ```
 git remote -v
 ```
  
 ```
 git clone <url>
 ```


Pushing to remote - How to Sync changes.

```
git push origin
```

Branching

To show the current working branch 
```
git branch --show-current
```
create a new branch
```
git branch <new_branch_name>
```
Switch to a branch
```
git checkout <branch_name>
```
Pushing this new branch to remote
```
git push -u origin <new_branch_name>
```
