# Git documentation
### To reset a pull or To rest a pull with specific time
```git reset --hard```
or
```git reset --hard branch-name@{"10 minute ago"}```

### To rename a branch from local to remote
```git branch -m old_branch new_branch```         :point_right: Rename branch locally

```git push origin :old_branch```                 :point_right: Delete the old branch   

```git push --set-upstream origin new_branch```   :point_right: Push the new branch, set local branch to track the new remote
