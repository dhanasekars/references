# Git Reference

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
