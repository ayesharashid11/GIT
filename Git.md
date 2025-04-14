# Initialize GIT

```git init```

```git status```

```git add .```

```git add <file_name>```

```git commit -m " " ```

```git config user.name " " ```

```git config user.email "" ```

```git restore --staged file```

```git rm --cached file.txt```

```git rm -f file.txt```

```git log``` shows commit, author name, date

```git log --online``` only shows commit.

# Git Branches
-> pointer to specific commit in git

```git checkout -b <branch>```  creates and switch new branch

```git branch``` show all branches

![image](https://github.com/user-attachments/assets/5aee8d89-1d81-4fe5-a804-4a4afe7ffe4f)

```git merge <branch>``` first checout from prev branch then merge.

# Git Remote Repo

```git remote add origin <URL>```

```git remote -v``` list all remote repos

```git push origin master```

```git clone <ssh link>```

```git fetch origin master``` after fetching do ```git merge origin/master```

```git pull origin master``` pull is actually 2 commands in one. 

```git rebase master``` rebase copy commits of one branch to another


-> cherry pick
```git cherry pick <hash_of_pick>```
create a copy of a commit onto our own branch

```git revert <hash>``` undoing commit changes
or
```git reset --soft HEAD~1``` / ```git reset --hard HEAD~1```
soft reset saves the commit changes while hard reset discards the commit chnages.


```git stash```
```git stash pop ```
```git stash list``` shows all the previous stashes made.

-> Git Reflog: 
-> used to undo hard  reset changes means it will bring back the data.
```git reflog```  
```git reset --hard <hash>```





