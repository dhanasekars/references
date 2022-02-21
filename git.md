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
git add
```

then 

```
git commit -m "initial commit"
```




To determine the details of the current local repo's remote details 
 ```
 git remote show origin 
 ```
 ```
 git remote -v
 ```
 
 Initalise git
 
 ```
 git init
 ```
 
 Clone a remote repo
 
 ```
 git clone <url>
 ```
 
 After making changes , to commit changes with message 

```
git add .
git commit -m "Story 182: fix benchmarks for speed"
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
