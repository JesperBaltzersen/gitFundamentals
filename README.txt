## PR cleanup
### Get a list of the branches that can be deleted/pruned
git remote prune origin --dry-run

### Acutally prune/delete references
git remote prune origin

### Delete local branch
git branch -d <branch>

