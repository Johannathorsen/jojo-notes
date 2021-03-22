# jojo-notes

- Update nvm: `nvm install stable --reinstall-packages-from=current`

- zsh package with git shortcuts & put numbers to changes: `scm_breeze`

- remove remote branches that no longer exists: `git remote prune origin`

- remove local branches that no longer exists on remote: ```git fetch -p && for branch in `git branch -vv | grep ': gone]' | awk '{print $1}'`; do git branch -D $branch; done```

- update ubuntu: `sudo apt update` -> `sudo apt dist-upgrade`

- see where e.g. node is ran from `which node`

- see where all nodejs exists `locate nodejs`

- update search index `sudo updatedb`

- squash the two latest commits and push as one: `git reset --soft HEAD~2` -> `git commit -m "message"` -> `git push --force` 
