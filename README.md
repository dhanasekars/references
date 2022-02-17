# python notes

## variable names

* always small letters
* Upper case has a special purpose, avoid in varialble names
* underscore_allowed
* use meaningful name


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
 
 
 # Conda reference
 
To create a new environment  
``` 
conda create -n <envname> python=3.8
```
Activate an environment
```
source activate <envname>
```
Update Anaconda navigator
```
conda update anaconda-navigator
````

After making changes , to commit changes with message 

```
git add .
git commit -m "Story 182: fix benchmarks for speed"
```

Pushing to remote - How to Sync changes.

```
git push origin
```

