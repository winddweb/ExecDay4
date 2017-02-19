Git Exercise 2 02/19/2017
Part I
1.
git reset (soft hard or mixed) moves the head back, and may also remove the changes you made. git revert creates a series of new commits that reverse the actions you did. Soft keeps the staged changes, mixed makes them unstaged. 

2.
Merge will create a new commit and merges the changes. Rebase will re-apply the changes with new commits to the base. 

3.
stash pop will apply and delete the changes after applying it. 
`git stash pop` is `git stash apply && git stash drop`
Use pop when you only need to apply the changes once(usually). And if it has conflicts pop will not drop the stash anyway.



