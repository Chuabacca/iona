# Git

Things I want to remember how to do in Git

### Squash
Combine two or more commits into one to clean up commit history

1. `git rebase -i HEAD~2` the number after `HEAD~` indicates the number of commits to be displayed
1. Replace `pick` with `squash` to select it as a commit to combine with the commit(s) above. Save.
1. Write the new commit message for the combined commit. Save.
1. If the commits have already been pushed to the remote, force push must be used `git push -f origin master`
  * **CAUTION** a force push will require others who have a different version of the repository to manually fix their local history

### Change Commit Message
When you need to travel back in time and re-write history

1. `git rebase -i HEAD~2` the number after `HEAD~` indicates the number of commits to be displayed
1. Replace `pick` with `reword` to select it as a commit to edit. Save.
1. Write the new message(s) for the selected commit(s)
1. If the commits have already been pushed to the remote, force push must be used
  * **CAUTION** a force push will require others who have a different version of the repository to manually fix their local history
